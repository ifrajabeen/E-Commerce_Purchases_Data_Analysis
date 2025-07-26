# 🛒 E-Commerce Purchases Data Analysis

This project explores and analyzes customer behavior from an e-commerce platform using Python and pandas. It answers key questions using data querying and visualization.

## 📁 File

- `E-Commerce_Purchases_DA.ipynb` — Main Jupyter Notebook for analysis

## 🧠 Objectives

- Understand customer demographics and purchasing behavior
- Extract meaningful insights from the dataset
- Practice using pandas, filtering, and logical conditions

## 🔍 Key Concepts Used

- Viewing data with `head()`, `info()`, `describe()`
- Filtering data using conditions:
  ```python
  df[df['Language'] == 'en']
  df[df['Job'] == 'Lawyer']
Using value_counts(), mean(), max() and similar functions

Applying logical operators (&, |) to filter with multiple conditions

Creating new columns with .apply() and custom functions
# 🧪 Sample Questions Answered
What is the average purchase price?

How many people have the job title "Lawyer"?

How many people made purchases with English as their language?

Who made the highest purchase?
# 🛠️ Requirements
Python 3.x

pandas

Jupyter Notebook (or Google Colab)
Install required libraries:
pip install pandas notebook
# ▶️ How to Run
Clone this repo or download the notebook file.

Open the .ipynb file in Jupyter Notebook or Google Colab.

Run the cells sequentially to view data insights.

# 📊 Output
This notebook gives:

Summary statistics

Insights into jobs, languages, and purchase patterns

Real-world pandas practice using e-commerce data
