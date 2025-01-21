# Titanic EDA (Exploratory Data Analysis)

This repository contains an exploratory data analysis (EDA) on the Titanic dataset. The analysis aims to explore and visualize key features of the dataset, such as passenger demographics, survival rates, and correlations that could influence survival. The goal is to provide insights into the factors affecting survival and perform basic statistical analysis.

---

## Dataset

The dataset used for this project is the Titanic dataset from [Kaggle's Titanic: Machine Learning from Disaster competition](https://www.kaggle.com/c/titanic/data). It contains information about passengers, including their age, gender, class, and whether they survived the Titanic disaster.

## Steps Taken

### 1. **Data Cleaning**
   - Handled missing values.
   - Checked for duplicated records to ensure clean data.
   - Created a new column to categorize passengers into age groups ("Child", "Adult", "Senior").

### 2. **Exploratory Data Analysis (EDA)**
   - Displayed the first 10 rows of the dataset to gain familiarity.
   - Visualized the distribution of passengers by gender, age, and survival rate.
   - Examined survival rates based on gender and passenger class.

### 3. **Statistical Analysis**
   - Calculated the mean, median, and mode for the 'Fare' and 'Age' columns.
   - Performed a t-test to determine if there's a significant difference in survival rates based on gender.
   - Performed a chi-square test to analyze survival rates across age groups.
