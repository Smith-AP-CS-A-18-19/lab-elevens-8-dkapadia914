# Elevens 8

Follow the instructions provided for Activity 8 in the student lab guide. This is more of an exploratory lab, so you will not need to copy any of your previous code into the repo. Answer the questions from the Student Guide in this document and ensure that you save and push the repo. You have one week to complete this lab.

1. Discuss the similarities and differences between *Elevens*, *Thirteens*, and *Tens*.

    * Answer: The similarities are the methods that are defined in the board class and the differences are those found in the the elevensboard class. Similarities are things like deal cards and is the game won while differences are methods such as is another play possible and is a move legal.

2. As discussed previously, all of the instance variables are declared in the `Board` class. But it is the `ElevensBoard` class that “knows” the board size, and the ranks, suits, and point values of the cards in the deck. How do the `Board` instance variables get initialized with the `ElevensBoard` values? What is the exact mechanism?

    * Answer: The Elevens board class uses inheritance to extend the instance variables and methods that are found from the board class.

3. Now examine the files `Board.java` and `ElevensBoard.java`, found in this repository. Identify the `abstract` methods in `Board.java`. See how these methods are implemented in `ElevensBoard`. Do they cover all the differences between *Elevens*, *Thirteens*, and *Tens* as discussed in question 1? Why or why not?

    * Answer: They are because they are abstract classes that must be found in all different games but have different implementation so they must be declared abstract in the abstract class but then the implementation is written in the ElevensBoard class.
