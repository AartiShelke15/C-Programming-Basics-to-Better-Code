# C Programming - Basics to Better Code

## About This Repository

This repository contains my step-by-step learning journey in C programming.

I started with a simple program to perform addition of two integers and gradually improved the same program by applying better programming practices such as:

- Meaningful variable names
- User input
- Meaningful output
- Function-based programming
- Separation of business logic
- Code documentation
- Test cases
- Code formatting and readability

The purpose of this repository is to understand how a simple working program can be improved into a cleaner, more readable, and maintainable program.

---

## Problem Statement

The user enters two integers and the program performs addition and displays the result.

### Basic Problem-Solving Steps

1. Understand the problem statement
2. Write the algorithm
3. Decide the programming language
4. Write the program
5. Test the program

---

## Program Progression

### program2.c - Basic Addition

A simple addition program using fixed values.

```text
10 + 11 = 21
```

The program works, but the variable names are not meaningful.

---

### program3.c - Meaningful Variable Names

The variable names are improved:

```c
iValue1
iValue2
iResult
```

This makes the code easier to understand.

---

### program4.c - User Input

The program is improved by taking two integer values from the user using `scanf()`.

This makes the program reusable for different inputs.

---

### program5.c - Meaningful Output

The output is improved from:

```text
21
```

to:

```text
Addition is : 21
```

This makes the output clearer to the user.

---

### program6.c - Separate Business Logic

The addition logic is moved from `main()` into a separate function:

```c
int Addition(int iNo1, int iNo2)
```

The `main()` function handles input and output, while the `Addition()` function performs the business logic.

---

### program7.c - Code Documentation

Function documentation and comments are added to make the program easier to understand and maintain.

The documentation includes:

- Function Name
- Input
- Output
- Description
- Date
- Author

---

### program8.c - Test Cases

Different test cases are used to verify the program.

| Input 1 | Input 2 | Expected Output |
|--------:|--------:|----------------:|
| 10   |      11 |          21 |
| 11   |       0 |          11 |
| 0    |      11 |          11 |
| 20   |      -9 |          11 |
| -9   |      20 |          11 |
| -20  |     -11 |         -31 |

The test cases include positive, negative, and zero values.

---

### program9.c - Improved Function Formatting

The function parameters are arranged on separate lines to improve readability.

```c
int Addition(
                int iNo1,
                int iNo2
            )
```

This formatting becomes useful when a function contains multiple parameters.

---

## Learning Progress

```text
Simple Program
      ↓
Meaningful Variable Names
      ↓
User Input
      ↓
Meaningful Output
      ↓
Separate Business Logic
      ↓
Code Documentation
      ↓
Testing
      ↓
Better Code Formatting
```

---

## Technologies Used

- C Programming (VS code)
- CMD
- GitHub

---

## Author

**Aarti Ramesh Shelke**

This repository is part of my programming and problem-solving learning journey.
