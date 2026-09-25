## Python Programming Test 

## Section A – Theory

**1. What is the output?**

```python
x = 10
y = 3
print(x // y + x % y)
```

A. `3`
B. `4`
C. `5`
D. `6`

---

**2. What will this return?**

```python
5 > 3 and 10 < 5
```

A. `True`
B. `False`
C. `10`
D. Error

---

**3. What does `continue` do inside a loop?**

A. Stops the program
B. Stops the loop permanently
C. Skips the current iteration
D. Restarts the loop

---

**4. What is the output?**

```python
def calculate(a, b=5):
    return a * b

print(calculate(4))
```

A. `9`
B. `20`
C. `4`
D. Error

---

**5. Which statement is used to immediately stop a loop?**

A. `skip`
B. `continue`
C. `stop`
D. `break`

---

### Q2. Short Answer Questions

**5 × 1 = 5**

1. What is the difference between `break` and `continue`?
2. What is the difference between a parameter and an argument?
3. Why do we use `return` in a function?
4. What is a nested loop?
5. What is the difference between `=` and `==`?

---

# Section B – Practical

## Q3. Number Analyzer

Write a program that takes a positive integer from the user and determines:

* Number of digits
* Sum of digits
* Number of even digits
* Number of odd digits
* Whether the number is divisible by 5

**Example:**

```text
Enter number: 25481

Number of digits: 5
Sum of digits: 20
Even digits: 3
Odd digits: 2
Divisible by 5: No
```

**Requirement:** Use a loop. Do not convert the number into a string.

---

## Q4. Electricity Bill Calculator

Create a function:

```python
calculate_bill(units)
```

Calculate the electricity bill according to:

| Units     |     Rate |
| --------- | -------: |
| 0–100     |  ₹5/unit |
| 101–200   |  ₹7/unit |
| 201–300   | ₹10/unit |
| Above 300 | ₹15/unit |

For example:

```text
Enter units: 250
Electricity Bill = ₹1850
```

Also add a **5% surcharge** if the calculated bill is greater than ₹2000.

Use a function and conditional statements.

---

## Q5. Multiplication Table Challenge

Write a program that:

1. Takes a number from the user.
2. Takes a starting value and ending value.
3. Prints the multiplication table within that range.
4. Does **not print multiples that are divisible by 3**.
5. Calculates and displays the sum of the printed results.

**Example:**

```text
Enter number: 5
Enter starting value: 1
Enter ending value: 10

5 x 1 = 5
5 x 2 = 10
5 x 4 = 20
5 x 5 = 25
5 x 7 = 35
5 x 8 = 40
5 x 10 = 50

Sum = 185
```

Use:

* `for` loop
* `continue`
* Operators

---

## Q6. Menu-Driven Calculator

Create a function:

```python
calculator(a, b, choice)
```

Display the following menu repeatedly:

```text
===== CALCULATOR =====
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Modulus
6. Exit
```

The program should:

* Take the user's choice.
* Take two numbers.
* Perform the selected operation.
* Handle division by zero.
* Continue displaying the menu until the user selects **6**.

**Requirement:** Use a function, loop, `if-elif-else`, and operators.
