# Task 20 — Sort Dataset Using Pandas

## Project Overview

This project demonstrates how to sort a dataset using Pandas. It covers numerical sorting, categorical sorting, ascending and descending orders, and sorting with multiple columns.

## Objectives

- Sort numerical values in ascending order.
- Sort numerical values in descending order.
- Sort categorical values alphabetically in both directions.
- Sort a DataFrame using multiple columns.
- Understand how sorting helps organize and analyze data.

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## Dataset Description

The project uses a manually created student performance dataset containing 12 fictional student records.

The columns are:

- `student_id`
- `name`
- `department`
- `age`
- `marks`
- `attendance`

## Sorting Operations

### 1. Ascending numerical sorting

`df.sort_values(by="marks", ascending=True)`

Arranges students from the lowest marks to the highest marks.

### 2. Descending numerical sorting

`df.sort_values(by="marks", ascending=False)`

Arranges students from the highest marks to the lowest marks.

### 3. Ascending categorical sorting

`df.sort_values(by="department", ascending=True)`

Arranges departments alphabetically from A to Z.

### 4. Descending categorical sorting

`df.sort_values(by="department", ascending=False)`

Arranges departments alphabetically from Z to A.

### 5. Multiple-column sorting

`df.sort_values(by=["department", "marks"], ascending=[True, False])`

Sorts departments alphabetically and sorts marks from highest to lowest within each department.

## Expected Results

Each sorting operation returns all 12 records. The records change order according to the specified sorting conditions.

## Project Files

- `Task_20_Sort_Dataset.ipynb` — Colab notebook and code.
- `student_performance.csv` — Sample dataset.
- `requirements.txt` — Dependencies.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.
- `screenshots/` — Actual notebook screenshots.

## Conclusion

This project demonstrates how Pandas `sort_values()` can organize numerical and categorical data. It also shows how sorting by multiple columns supports more detailed analysis.
