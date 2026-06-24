# Typing Tester using Python

## Overview
Typing Tester is a simple Python-based mini project that helps users test and improve their typing speed and accuracy. The program displays a random sentence, measures the time taken by the user to type it, and calculates typing performance metrics such as Words Per Minute (WPM) and accuracy percentage.

This project is useful for practicing typing skills while also demonstrating basic Python programming concepts such as functions, lists, loops, and time-based calculations.

---

## Features
- Random sentence generation for typing practice
- Measures total time taken to complete typing
- Calculates typing speed in Words Per Minute (WPM)
- Checks typing accuracy by comparing user input with the original sentence
- Simple command-line interface (CLI)

---

## Technologies Used
- :contentReference[oaicite:0]{index=0}
- Built-in Python libraries:
  - `time`
  - `random`

---

## How It Works
1. The program selects a random sentence from a predefined list.
2. The user is asked to type the displayed sentence.
3. The timer starts when the sentence is shown.
4. After typing, the timer stops.
5. The program calculates:
   - Time taken
   - Number of words typed
   - Typing speed (WPM)
   - Accuracy percentage

---

## Installation
1. Make sure Python is installed on your system.
2. Clone this repository:

```bash
git clone <your-repository-link>
```

3. Navigate to the project folder:

```bash
cd typing-tester
```

4. Run the program:

```bash
python typing_tester.py
```

---

## Example Output

```text
Type the following sentence as fast as you can:
Python is a versatile programming language.

Your input:
Python is a versatile programming language.

Results:
Time taken: 12.53 seconds
Words typed: 6
Typing speed: 28.74 words per minute
Accuracy: 100.00%
```

---

## Learning Outcomes
Through this project, I learned:
- Working with Python functions
- Using built-in libraries
- Measuring execution time
- Performing string comparison
- Building command-line applications

---

## Future Improvements
- Add graphical user interface using `tkinter`
- Add difficulty levels
- Store high scores
- Include more typing test sentences
- Improve accuracy calculation with advanced error detection

---

## Author
Developed by **Sania Aftab** as a Python mini project to enhance programming and problem-solving skills.
