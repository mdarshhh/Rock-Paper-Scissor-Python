# Project Statement

## Rock Paper Scissors Game

**Student Name:** Mohd Arasalan  
**Registration Number:** 26BCE11205  
**University:** VIT Bhopal University

### Problem Statement

The aim of this project is to create a simple Rock Paper Scissors game using Python.

The program allows a user to play Rock Paper Scissors against the computer. The computer makes its choice randomly from rock, paper, and scissors. The program then compares the user's choice with the computer's choice and displays whether the user won or lost.

The program also keeps track of how many times the user and the computer win.

### Working of the Program

The program starts by importing Python's `random` module. Two variables are used to store the number of wins for the user and the computer.

The choices `rock`, `paper`, and `scissors` are stored in a list. Inside a `while` loop, the user is asked to enter a choice.

If the user enters `q`, the loop stops. If the input is not one of the three valid choices, the program continues to the next iteration.

For a valid choice, the computer selects a random number from 0 to 2. This number is used to select rock, paper, or scissors from the list.

The program then checks the winning conditions:

- If the user chooses rock and the computer chooses scissors, the user wins.
- If the user chooses paper and the computer chooses rock, the user wins.
- If the user chooses scissors and the computer chooses paper, the user wins.
- In all other cases, the program counts the result as a computer win.

At the end, the program prints the total number of user wins and computer wins and displays a goodbye message.

### Objective

The objective of this project is to practice basic Python programming concepts such as:

- Variables
- Lists
- Loops
- Conditional statements
- User input
- Random number generation
- Counters

### Input

The program accepts:

- `rock`
- `paper`
- `scissors`
- `q` to quit the game

### Output

The program displays:

- The computer's selected choice.
- Whether the user won or lost each round.
- Total number of user wins.
- Total number of computer wins.
- A goodbye message when the game ends.

### Conclusion

This project implements a basic Rock Paper Scissors game using Python. It demonstrates how a loop, conditional statements, user input, a list, and random number generation can be combined to make a simple interactive program.
