# Comprehensive pandas Tutorial for Data Analysis

![Python](https://img.shields.io/badge/Python-3.13.5-blue.svg)
![pandas](https://img.shields.io/badge/pandas-2.2.3-lightgrey.svg)

A comprehensive Jupyter Notebook designed as a practical and hands-on guide to **pandas**,  
 one of the most powerful and widely-used Python libraries for data manipulation and analysis.  
 This tutorial covers foundational concepts through intermediate data processing techniques,  
 demonstrated with both synthetic data and the classic Titanic dataset.

---

## Topics Covered

This tutorial dives into essential pandas concepts, including:

- **The core data structures (Series and DataFrame)**:<br>  
  Introduces the basic building blocks of pandas: the Series, a one-dimensional labeled array, and the DataFrame, a two-dimensional tabular structure.  
  Covers creating these objects from lists and dictionaries, understanding their attributes, and how to manipulate and access their data effectively.

- **Loading, Saving and Discovering data**:  <br>
  Demonstrates how to load datasets from external files (e.g., CSV), save processed DataFrames back to disk, and use exploratory methods to quickly understand dataset structure and content, including `.head()`, `.tail()`, `.info()`, and `.describe()`.

- **Selection, Indexing and Filtering**:  <br>
  Explains methods to select and filter rows and columns using label-based (`.loc`), position-based (`.iloc`), and Boolean indexing, helping you subset data efficiently and make conditional queries.

- **Data cleaning**:  <br>
  Covers identifying and handling missing values (`NaN`), using functions like `.isna()`, `.fillna()`, and `.dropna()`.  
  Also discusses replacing missing or malformed data entries (e.g., filling missing cabin values with `"Unknown"`), renaming columns, and cleaning inconsistencies.

- **Grouping and Aggregation**:  <br>
  Introduces grouping data with `.groupby()`, applying aggregation functions like `.mean()`, `.sum()`, `.count()`, and custom summaries to extract insights, such as calculating survival rates by passenger class or gender.

- **Pivot table**:  <br>
  Demonstrates using `pivot_table()` to create multi-dimensional tables summarizing data, useful for exploring relationships and aggregations across different categorical variables.

- **Working with Text Data `.str`**:  <br>
  Utilizes pandas string methods accessed via `.str` for vectorized text manipulation.  
  Includes extracting titles from passenger names, splitting strings, pattern matching with regex, string replacement, and case transformations.

- **Intro for ML using pandas**:  <br>
  Introduces basic feature engineering and preprocessing steps for machine learning workflows, including encoding categorical variables as numeric, creating new features like family size, and transforming data with one-hot encoding to prepare for modeling.

