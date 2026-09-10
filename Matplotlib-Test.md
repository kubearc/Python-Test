## Matplotlib Practical Task — 50 Marks

### Dataset

Use the following data:

```python
import numpy as np
import matplotlib.pyplot as plt

months = np.array(["Jan", "Feb", "Mar", "Apr", "May", "Jun"])
sales = np.array([120, 150, 180, 140, 200, 230])
expenses = np.array([80, 90, 100, 95, 110, 120])
students = np.array([25, 30, 28, 35, 40, 45])
marks = np.array([65, 72, 80, 55, 90, 68, 75, 88, 60, 95])
```

### Question 1 — Line Plot (10 Marks)

Create a line plot showing **Sales** and **Expenses** for each month.

Requirements:

* Add a title: **Monthly Sales and Expenses**
* Add X-axis label: **Month**
* Add Y-axis label: **Amount**
* Add a legend

---

### Question 2 — Bar Chart (10 Marks)

Create a **bar chart** showing the number of students for each month.

Requirements:
* X-axis → Months
* Y-axis → Number of Students
* Add a suitable title
* Add X and Y labels
* Display the chart

**Bonus:** Display the value of each bar above the bar.

---

### Question 3 — Scatter Plot (10 Marks)

Create a scatter plot using:

* X-axis → `students`
* Y-axis → `sales`

Requirements:

* Add a suitable title
* Add X-axis and Y-axis labels
* Add a legend
* Display the plot

---

### Question 4 — Histogram (10 Marks)

Use the `marks` array to create a histogram.

Requirements:

* Use **5 bins**
* Add a suitable title
* Add X-axis label: **Marks**
* Add Y-axis label: **Number of Students**
* Display the histogram

**Question:** Which range of marks contains the highest number of students?

---

### Question 5 — Subplots (10 Marks)

Create **4 plots in one figure** :

1. **Line plot** → Sales by month
2. **Bar chart** → Expenses by month
3. **Scatter plot** → Students vs Sales
4. **Histogram** → Distribution of Marks


Add a suitable title to each subplot and display the complete figure.
