# Python Assignment 3: While Loop, For Loop and Function

This assignment has three small Python programs that practise loops, control statements and functions.

**File:** `Assignment 03 For loop,while loop and function.py`

---

## Requirements

- Python 3.6 or newer (tested with Python 3.12)
- No extra libraries needed (only the built-in `random` module)

## How to Run

1. Open the `.py` file in VS Code (or any editor).
2. Click **Run** once, or use the terminal:
   ```
   python "Assignment 03 For loop,while loop and function.py"
   ```
3. When a prompt appears, type your answer in the terminal and press **Enter**.
4. The parts run in order: Part 1, then Part 2, then Part 3.

> Tip: Don't click Run again while the program is waiting for input. Type your answer instead.

---

## Part 1: Number Guessing Game (while loop)

**Concepts:** `while`, `if/elif/else`, `continue`, `break`, `while ... else`, `random.randint()`

- The program picks a secret number between 1 and 10.
- The user gets 3 attempts.
- Out-of-range guesses are rejected using `continue` (no attempt is used).
- A correct guess ends the game using `break`.
- If all attempts are used, the `else` block prints "Better luck next time!".

**Sample output:**
```
Guess the number (between 1 and 10): 2
Too low. Try again.
Guess the number (between 1 and 10): 15
Your guess is out of range. Please guess a number between 1 and 10.
Guess the number (between 1 and 10): 5
Too high. Try again.
Guess the number (between 1 and 10): 3
Congratulations! You guessed the correct number.
```

---

## Part 2: Multiplication Table Generator (for loop)

**Concepts:** `for`, `range()`, `input()`, `int()`

- Asks for a number.
- Prints its multiplication table from 1 to 10.

**Sample output:**
```
Enter the number for which you want the multiplication table: 5
5 x 1 = 5
5 x 2 = 10
...
5 x 10 = 50
```

---

## Part 3: BMI Calculator (function)

**Concepts:** `def`, `return`, `float()`, f-strings

- `calculate_bmi(weight, height)` returns `weight / (height ** 2)`.
- The result is printed with 2 decimal places.

**Sample output:**
```
Enter your weight in kg: 58
Enter your height in meters: 1.62
Your BMI is: 22.10
```

---

## Common Errors

| Error | Cause | Fix |
|-------|-------|-----|
| `ValueError: invalid literal for int()` | Typed text or a command instead of a number | Type only a number at the prompt |
| `IndentationError` | Wrong spacing inside loops or functions | Use 4 spaces consistently |
| `NameError` | Misspelled variable name | Check spelling and capitalisation |

---

## Author

Name: ____________________
Course / Batch: ____________________
Date: ____________________
