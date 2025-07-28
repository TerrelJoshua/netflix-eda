# Netflix Titles Data Analysis

##  Overview
This project performs exploratory data analysis (EDA) on the Netflix titles dataset to uncover insights about content trends, duration patterns, and the evolution of content over time.

The dataset was cleaned, transformed, and visualized using Python libraries such as Pandas and Matplotlib. This project is suitable for aspiring data analysts to demonstrate EDA, data cleaning, and visualization skills.

---

## Tools & Libraries Used
- Python 3.8
- Pandas
- Matplotlib
- Jupyter Notebook (or any IDE)
- Dataset: 'netflix_titles.csv' from Kaggle

---

##  Data Cleaning & Transformation
- Checked column names, shape, and data types.
- Converted 'date_added' column to datetime format.
- Split the 'duration' column into two: 'duration_value' (numeric) and 'duration_unit' (minutes/seasons).
- Removed duplicates and unnecessary columns ('description').
- Handled missing values and created a new 'year' column from the 'date_added'.

---

##  Key Analysis Performed
- Counted how many titles were added each year.
- Identified the year with the highest number of new content additions.
- Extracted and cleaned duration values for better filtering and visualization.

---

## Visualization
A horizontal bar chart was plotted to show:
-  The number of Netflix titles added per year (2008–2021)

---

## Key Insights
- The number of titles added increased rapidly after 2016, peaking around 2019–2020.
- Most content entries have complete 'duration' data and consistent formatting after cleaning.
- Splitting duration helps distinguish between movies (minutes) and TV shows (seasons).

---

