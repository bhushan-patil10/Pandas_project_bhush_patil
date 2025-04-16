# 🐼 Pandas

**Pandas** is a powerful Python library primarily used for data manipulation and analysis, especially working with structured data like tabular data (DataFrames). It's a fundamental tool in the PyData ecosystem, known for its ability to handle diverse data formats, including CSV, Excel, and SQL. Pandas provides efficient data structures and functions for cleaning, exploring, transforming, and analyzing data, making it a favorite among data scientists and analysts.

---

## 📚 About the Project

This project contains practical examples and tutorials demonstrating how to work with datasets using the `Pandas` library. From loading and exploring data to cleaning, transforming, joining, and analyzing it, this project serves as a solid foundation for learning data analysis with Pandas.

---

## ✨ Key Features & Methods Used

### 📦 Data Structures in Pandas

- **Series**: One-dimensional labeled array (like a column in Excel)
  - Syntax: `pandas.Series(data=None, index=None, dtype=None, name=None, copy=None)`
  - Has `index` and `data`
- **DataFrames**: Two-dimensional tabular data (like an Excel sheet or SQL table)

### 🔧 Data Importing and Inspection

- `pd.read_csv()`, `pd.read_excel()`, `pd.read_sql()`
- `df.head()`, `df.tail()`, `df.info()`, `df.describe()`

### 🔍 Indexing and Structure

- `set_index()`: Set an existing column as the index
- `reset_index()`: Reset the index to default
- Dictionaries to Series/DataFrame: Keys become indices, values become data

### 🧮 Data Manipulation & Analysis

- Filtering rows using conditions
- `apply()`, `map()`, `replace()`
- Arithmetic operations and statistical functions: `mean()`, `sum()`, `min()`, `max()`
- Grouping data: `groupby()`, `agg()`, `pivot_table()`
- Merging: `merge()`, `concat()`, `join()`, including `left join`
- Working with `datetime`: `pd.to_datetime()`, `.dt.year`, `.dt.month`

### 🧪 Additional Tools

- Importing essential libraries: `pandas`, `numpy`, `datetime`
- Handling missing values: `isnull()`, `fillna()`, `dropna()`

---

## 🛠️ Technologies Used

- Python 
- [Pandas](https://pandas.pydata.org/)
- Jupyter Notebook 

---


