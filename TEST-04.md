## Python Test (50 Marks)

### Part A: Theory (20 Marks)

 Q1. What is the purpose of the `range()` function in Python? Write its syntax and one example. (4 Marks)

Q2. What is an Array in Python? How is it different from a List? (4 Marks)

Q3. What is an Iterator? Explain the use of `iter()` and `next()` with an example. (4 Marks)

Q4. What is the purpose of a Function in Python? Differentiate between built-in and user-defined functions. (4 Marks)

Q5. Explain:

- Regular Expressions (Regex)
- Exception Handling (`try-except`) (4 Marks)

### Part B: Practical Task (30 Marks)

### Student Marks Management System

Create a Python program that performs the following operations:

### Step 1: Student Count (3 Marks)

* Ask the user to enter the number of students.
* Use **try-except** to handle invalid input.

Example:

```python
Enter number of students: 5
```

---

### Step 2: Store Marks Using Array (5 Marks)

* Import the `array` module.
* Use `range()` and a `for` loop to accept marks for all students.
* Store marks in an integer array.

Example:

```python
Enter marks of Student 1: 80
Enter marks of Student 2: 75
Enter marks of Student 3: 90
```

---

### Step 3: Create Functions (5 Marks)

Create the following user-defined functions:

```python
calculate_average()
find_grade()
```

Requirements:

* `calculate_average()` should return the average marks.
* `find_grade()` should return a grade based on the average.

| Average Marks | Grade |
| ------------- | ----- |
| 90 and above  | A     |
| 80 – 89       | B     |
| 70 – 79       | C     |
| Below 70      | D     |

---

### Step 4: Use Iterator (5 Marks)

* Create an iterator from the marks array using `iter()`.
* Display all marks using `next()`.

Example:

```python
Marks Using Iterator:
80
75
90
```

---

### Step 5: Email Validation Using Regex (5 Marks)

* Ask the user to enter an email address.
* Use Regular Expression (`re`) to validate the email.

Example:

```python
Enter Email: student@gmail.com
Valid Email
```

---

### Step 6: Generate Report (7 Marks)

Display the following:

Sample Output:

```python
----- STUDENT REPORT -----

Total Marks : 245
Average Marks : 81.67
Highest Marks : 90
Lowest Marks : 75
Grade : B

Email Status : Valid
```
