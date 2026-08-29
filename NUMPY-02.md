# NumPy Practical Test — Python

**Level:** Beginner → Intermediate   
**Total Marks:** 50  
**Bonus:** +5 marks

## Instructions
- Write and execute actual Python code for every question.
- Use NumPy functions wherever possible.
- Do not use Pandas.
- For questions asking for a specific output, your code should produce that output rather than manually typing the answer.
- Assume:

```python
import numpy as np
```

---

# Part 1 — Array Creation & Basic Operations
**10 Marks**

## Q1. Create a NumPy array — 2 marks
Create a 1-D NumPy array containing `10, 20, 30, 40, 50`.

Then print:
1. The array
2. Its data type
3. Its number of dimensions
4. Its shape
5. Its size

## Q2. Create a 3×3 matrix — 2 marks
Create:

```text
1 2 3
4 5 6
7 8 9
```

Print the array, shape, number of dimensions, and total number of elements.

## Q3. Array of zeros and ones — 2 marks
Create:
1. A 3×4 array containing only zeros.
2. A 2×5 array containing only ones.

Print both arrays.

## Q4. Range — 2 marks
Using NumPy, create an array containing all even numbers from **2 to 20**.

Expected:
```text
[ 2  4  6  8 10 12 14 16 18 20]
```

## Q5. Identity matrix — 2 marks
Create a **5×5 identity matrix** using NumPy.

---

# Part 2 — Indexing & Slicing
**10 Marks**

Given:

```python
arr = np.array([10, 20, 30, 40, 50, 60, 70, 80])
```

## Q6. Basic indexing — 2 marks
Print:
1. First element
2. Last element
3. Third element
4. Second-last element

## Q7. Slicing — 2 marks
Using slicing, print:
```text
[20 30 40 50]
```

## Q8. Every second element — 2 marks
Using slicing, print:
```text
[10 30 50 70]
```

## Q9. Reverse an array — 2 marks
Reverse the array using NumPy slicing.

Expected:
```text
[80 70 60 50 40 30 20 10]
```

## Q10. 2D indexing — 2 marks
Given:

```python
matrix = np.array([
    [10, 20, 30],
    [40, 50, 60],
    [70, 80, 90]
])
```

Print:
1. `50`
2. The second row
3. The third column
4. The first two rows

---

# Part 3 — Mathematical Operations
**10 Marks**

Given:

```python
arr = np.array([10, 20, 30, 40, 50])
```

## Q11. Statistics — 2 marks
Calculate using NumPy:
- Sum
- Mean
- Minimum
- Maximum

## Q12. Multiplication — 2 marks
Multiply every element by `2`.

Expected:
```text
[ 20  40  60  80 100]
```

## Q13. Addition — 2 marks
Add `5` to every element.

Expected:
```text
[15 25 35 45 55]
```

## Q14. Standard deviation and variance — 2 marks
Calculate using NumPy:
- Standard deviation
- Variance

## Q15. Array arithmetic — 2 marks
Given:

```python
a = np.array([1, 2, 3, 4, 5])
b = np.array([10, 20, 30, 40, 50])
```

Perform:
```text
a + b
a - b
a * b
a / b
```

---

# Part 4 — 2D Arrays
**10 Marks**

Given:

```python
matrix = np.array([
    [10, 20, 30],
    [40, 50, 60],
    [70, 80, 90]
])
```

## Q16. Row operations — 2 marks
Calculate the **sum of each row**.

Expected:
```text
[ 60 150 240]
```

## Q17. Column operations — 2 marks
Calculate the **sum of each column**.

Expected:
```text
[120 150 180]
```

## Q18. Find maximum — 2 marks
Find the maximum value:
1. In the entire matrix
2. From each row
3. From each column

## Q19. Transpose — 2 marks
Transpose the matrix.

Expected:
```text
[[10 40 70]
 [20 50 80]
 [30 60 90]]
```

## Q20. Reshape — 2 marks
Create:

```python
arr = np.arange(1, 13)
```

Reshape it into **4 × 3**.

Expected:
```text
[[ 1  2  3]
 [ 4  5  6]
 [ 7  8  9]
 [10 11 12]]
```

---

# Part 5 — Practical Problem
**10 Marks**

## Q21. Student Marks Analysis — 10 marks

You are given the marks of 5 students in 4 subjects:

```python
marks = np.array([
    [78, 85, 92, 88],
    [65, 70, 72, 68],
    [90, 95, 94, 91],
    [55, 60, 58, 62],
    [82, 80, 85, 87]
])
```

Write a NumPy program that calculates:

### A. Total marks of each student — 2 marks
Calculate the total marks for every student.

### B. Average marks of each student — 2 marks
Calculate the average marks for every student.

### C. Highest mark in each subject — 2 marks
Find the highest mark obtained in each subject.

### D. Student with the highest total marks — 2 marks
Print the **student number** as well as the total marks.

### E. Students with average ≥ 75 — 2 marks
Count how many students have an average of at least `75`.

---

# Bonus Challenge
**+5 Marks**

## Q22. NumPy Filtering

Given:

```python
arr = np.array([12, 5, 18, 7, 25, 3, 30, 14, 9, 20])
```

Using NumPy, create a new array containing only values **greater than 15**.

Expected:
```text
[18 25 30 20]
```

Then calculate:
- Number of values greater than 15
- Their sum
- Their average

---

# Marking Scheme

| Section | Marks |
|---|---:|
| Array Creation | 10 |
| Indexing & Slicing | 10 |
| Mathematical Operations | 10 |
| 2D Arrays | 10 |
| Practical Problem | 10 |
| **Total** | **50** |
| **Bonus** | **+5** |


## Test Rules

Try to solve this test **without looking at NumPy solutions or documentation**.

After completing it, submit your Python code for grading. The test can be evaluated **out of 50 (+5 bonus)**, with mistakes identified and specific NumPy concepts recommended for further practice.
