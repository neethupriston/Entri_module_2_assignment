README – Module 2 Assignment
📌 Project Overview

This assignment demonstrates data preprocessing and exploratory data analysis (EDA) using Python. The dataset represents records from ABC Company and includes fields such as employee height (generated), salary, and other attributes.

The notebook covers essential data analysis steps including:

Importing libraries

Loading the dataset

Data cleaning

Descriptive statistics

Handling missing values

Identifying duplicates

This assignment is part of a larger module focused on understanding NumPy, pandas, and basic EDA techniques.

📚 Technologies Used

Python 3

NumPy

Pandas

Matplotlib

Seaborn

Jupyter Notebook

📂 Contents of the Notebook
1. Importing Required Libraries

The notebook imports essential libraries for numerical computing, data manipulation, and visualization:

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

2. Loading the Dataset

The dataset is loaded from a CSV file:

df = pd.read_csv("ABC Company.xlsx - Sheet1.csv")

3. Feature Engineering

A new column Height is created using NumPy’s random integer generator:

df['Height'] = np.random.randint(150, 180, size=len(df))

4. Descriptive Statistics

Basic statistical summary of the dataset:

df.describe()

5. Checking for Missing Values

To identify how many values are missing in each column:

df.isnull().sum()

6. Checking for Duplicate Records

To detect duplicate rows in the dataset:

df.duplicated().sum()

📊 Summary

This notebook demonstrates key data preprocessing tasks:

Data loading and inspection

Generating new features

Summary statistics

Missing value detection

Duplicate detection

These skills are essential for anyone learning data science, machine learning, or data analytics.

📝 How to Run This Notebook

Install the required Python libraries:

pip install numpy pandas matplotlib seaborn


Open Jupyter Notebook:

jupyter notebook


Load Module_2_Assignment.ipynb

Ensure the dataset CSV is in the correct path.

Run all cells sequentially.
