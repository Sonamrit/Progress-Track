# 📘 Pandas DataFrame Basics (Jupyter Notebook Practice)

This document contains a summary of what I studied today related to **Pandas DataFrame** in Python using **Jupyter Notebook**.

---

## 🔹 What is a DataFrame?

A **DataFrame** is a 2-dimensional labeled data structure with columns of potentially different types.  
It is similar to a spreadsheet or SQL table.  
It is a main object in Pandas and is used to represent data with rows and columns (tabular or Excel spreadsheet-like data).

---

## 🔹 Importing Pandas

```python
import pandas as pd
🔹 Creating a DataFrame using Python Dictionary
python
Copy
Edit
weather_data = {
    'day': ['1/1/2017', '1/2/2017', '1/3/2017', '1/4/2017', '1/5/2017', '1/6/2017'],
    'temperature': [32, 35, 28, 24, 32, 31],
    'windspeed': [6, 7, 2, 7, 4, 2],
    'event': ['Rain', 'Sunny', 'Snow', 'Snow', 'Rain', 'Sunny']
}
df = pd.DataFrame(weather_data)
df
🔹 Displaying Data
Head (First 5 Rows)

python
Copy
Edit
df.head()
Tail (Last 5 Rows)

python
Copy
Edit
df.tail()
🔹 Indexing and Slicing
Accessing a single column

python
Copy
Edit
df['event']
Accessing multiple columns

python
Copy
Edit
df[['day', 'event']]
Row slicing

python
Copy
Edit
df[2:5]
🔹 Type of DataFrame
python
Copy
Edit
type(df)
🔹 Operations with DataFrame
python
Copy
Edit
df.max()
df.min()
df.mean()
df.describe()
🔹 Conditional Selection
python
Copy
Edit
df[df['temperature'] > 30]
🔹 Common Pandas Operations List
python
Copy
Edit
df.head()
df.tail()
df.describe()
df.info()
df.columns
df.dtypes
df.shape
df.isnull()
df.drop()
df.fillna()
🔹 Index Operations
Set Index



