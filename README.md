# NextGen_internship_week3
# Internship Weekly Report - Week 3

**Name:** Sandeep Ravaji Patel
**Domain:** Data Science
**Week Number:** Week 3

## Task Description

**Objective:** To develop skills in data visualization and exploratory data analysis (EDA) using real-world datasets, focusing on generating meaningful visual insights and handling missing values effectively.

**Tasks Completed:**

### Data Visualization:
- Plotted bar charts, histograms, and scatter plots using `Matplotlib` and `Seaborn`.
- Used `plt.bar`, `plt.hist`, `sns.scatterplot`, and `sns.heatmap` to generate clean and informative graphs.
- Compared visual outputs from different datasets (`bengaluru_house_prices.csv` and `Pokemon.csv`).

### Exploratory Data Analysis (EDA):
- Identified and handled missing data using `isnull()`, `dropna()`, and `fillna()`.
- Conducted correlation analysis using `corr()` and visualized it with heatmaps.
- Analyzed distribution and relationship of features such as price, area, and Pokémon statistics.

**Tools Used:**

- Matplotlib
- Seaborn
- Pandas
- Jupyter Notebook

## Challenges Faced

**Missing Data Issues:**
- Some columns had extensive missing values.
- **Resolution:** Used median/mode imputation or dropped rows depending on data quality and quantity.

**Inconsistent Data Types:**
- Some numeric columns were read as strings due to formatting issues.
- **Resolution:** Cleaned and typecasted columns using `astype(float)` after cleaning symbols.

**Plot Formatting and Readability:**
- Legends and axis labels sometimes overlapped or were unreadable.
- **Resolution:** Added `tight_layout()`, rotated ticks, and adjusted figure size for clarity.

## Learning Outcome

**Data Visualization Mastery:**
- Gained confidence using Matplotlib and Seaborn to build clear and impactful visualizations.

**EDA Techniques:**
- Performed real-world data exploration with correlation analysis, value counts, and distribution plots.

**Data Cleaning:**
- Improved handling of null values and inconsistent formats across datasets.

## Next Steps

For **Week 4**, the focus will be on:
- Machine Learning Basics: Introduction to supervised models.
- Modeling Practice: Implementing Linear Regression.
- Data Preparation: Splitting data into training and testing sets.

## Resources

- Matplotlib: [Matplotlib Guide](Matplotlib Guide)
- Seaborn: [Seaborn Documentation](Seaborn Documentation)
- Dataset 1: [Bengaluru House Prices – CSV](bengaluru_house_prices.csv)
- Dataset 2: [Pokémon Dataset – CSV](Pokemon.csv)
