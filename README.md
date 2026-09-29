# Rock Paper Scissors Game

**Student Name:** Mohd Arasalan  
**Registration Number:** 26BCE11205  
**University:** VIT Bhopal University


---

## About the Project

This is a simple **Rock Paper Scissors** game made using Python.

In this program, the user plays against the computer. The user can choose **rock**, **paper**, or **scissors**. The computer randomly selects one of the three choices.

The program continues to take choices until the user enters **Q** to quit.

---

## How the Program Works

1. The `random` module is imported to make the computer's choice random.
2. Two counters are created:
   - `user_wins` to count the user's wins.
   - `computer_wins` to count the computer's wins.
3. The three choices are stored in a list:
   - rock
   - paper
   - scissors
4. The program asks the user to enter a choice.
5. If the user enters `Q`, the game stops.
6. If the input is not one of the valid choices, the program asks again.
7. The computer selects a random choice.
8. The program checks the user's choice against the computer's choice.
9. The winner's counter is increased.
10. When the user quits, the program displays the total wins of the user and the computer.

---

## Rules Used in the Program

The program checks these winning conditions:

- Rock beats Scissors.
- Paper beats Rock.
- Scissors beats Paper.

If none of these conditions is true, the program counts it as a computer win.

---

## Python Concepts Used

This project uses some basic Python concepts:

- `import random`
- Variables
- Lists
- `while` loop
- `if`, `elif`, and `else`
- `input()`
- `print()`
- `random.randint()`
- `break`
- Counters

---

## How to Run

Make sure Python is installed on your computer.

Then run the Python file:

```bash
python "Project Rock Paper Scissor.py"
```

The program will show:

```text
Type rock/paper/scissors or Q to quit:
```

Enter `rock`, `paper`, or `scissors` to play.

Enter `Q` when you want to stop the game.

---

## Example

```text
Type rock/paper/scissors or Q to quit: rock
computer picked scissors.
you won!

Type rock/paper/scissors or Q to quit: paper
computer picked scissors.
you lost!

Type rock/paper/scissors or Q to quit: Q

you won 1 times.
the computer won 1 times.
goodbye!
```

The exact computer choices will be different because they are selected randomly.

---

## Project File

- `Project Rock Paper Scissor.py` — Python source code for the game.

---

## Student Details

**Name:** Mohd Arasalan  
**Registration Number:** 26BCE11205  
**Project:** Rock Paper Scissors Game  
**University:** VIT Bhopal University


