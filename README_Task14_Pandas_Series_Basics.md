# Task 14 - Pandas Series Basics

## Objective
Learn Pandas Series by creating, indexing, filtering, performing arithmetic operations, and basic statistical analysis.

## Tools Required
- Python
- Pandas
- Jupyter Notebook

## Import Pandas
```python
import pandas as pd
```

## Create a Series
```python
numbers = pd.Series([10,20,30,40,50])
print(numbers)
```

## Custom Index
```python
marks = pd.Series([85,90,95], index=["Math","Science","English"])
print(marks)
```

## Access Elements
```python
print(numbers[2])
print(marks["Science"])
```

## Filtering
```python
marks = pd.Series([75,85,90,60,95])
print(marks[marks>80])
```

## Arithmetic Operations
```python
numbers = pd.Series([10,20,30])
print(numbers+5)
print(numbers-5)
print(numbers*2)
print(numbers/2)
```

## Statistical Functions
```python
marks = pd.Series([80,90,85,95,70])
print(marks.sum())
print(marks.mean())
print(marks.max())
print(marks.min())
print(marks.count())
print(marks.describe())
```

## Student Marks Example
```python
students = pd.Series([85,92,76,90,88], index=["Alice","Bob","Charlie","David","Eva"])
print(students)
print(students[students>85])
print(students.mean())
print(students.describe())
```

## Sales Example
```python
sales = pd.Series([1500,2000,1800,2500], index=["Jan","Feb","Mar","Apr"])
print(sales)
print(sales.sum())
print(sales.mean())
```

## Conclusion
This task covers the fundamentals of Pandas Series including creation, indexing, filtering, arithmetic operations, and statistical functions.
