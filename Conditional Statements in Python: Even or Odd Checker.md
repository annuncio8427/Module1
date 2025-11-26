# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program

```python
a = int(input("Enter a number: "))
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```

## Output

```
Enter a number: 4
EVEN
```

```
Enter a number: 7
ODD
```

## Result

The program successfully determines whether a number is even or odd using the modulo operator. When the user inputs 4, the program outputs "EVEN" since 4 % 2 == 0. When the user inputs 7, it outputs "ODD" since 7 % 2 != 0. This demonstrates the use of conditional statements (if-else) in Python for decision making.
