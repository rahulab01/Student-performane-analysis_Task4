# Student-performane-analysis_Task4
Data analysis using python- internship task 4

# Titanic Mini EDA Project


# Project Overview

This project performs a **Mini Exploratory Data Analysis (EDA)** on the Titanic dataset using Python libraries such as pandas, matplotlib, and seaborn.

The analysis includes:

* Data cleaning
* Handling missing values
* Feature engineering
* Data visualization
* Insights and conclusions

The goal is to understand the factors that affected passenger survival on the Titanic.

---

# Dataset

Dataset Used: **Titanic Dataset**

Common columns in the dataset:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# Project Workflow

## 1. Data Cleaning

* Filled missing values in `Age`
* Filled missing values in `Embarked`
* Dropped unnecessary column `Cabin`

## 2. Feature Engineering

Created new features:

* `FamilySize`
* `AgeGroup`

## 3. Data Visualization

The project includes the following visualizations:

1. Histogram of Age Distribution
2. Bar Chart of Survival by Gender
3. Boxplot of Fare by Passenger Class
4. Scatterplot of Age vs Fare
5. Correlation Heatmap

---

# Key Insights

* Females had a higher survival rate than males.
* First-class passengers survived more frequently.
* Most passengers were young adults.
* Higher ticket fares were associated with higher survival chances.
* Passenger class strongly influenced survival.

---

# Project Structure

```bash
├── Titanic-Dataset.csv
├── internship_task4.ipynb
├── README.md
```

---

# How to Run

## Step 1: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

## Step 2: Run the Notebook

Open Jupyter Notebook or Google Colab and run:

```bash
internship_task4.ipynb
```

---

# Sample Visualizations

* Age Distribution Histogram
* Survival Rate by Gender
* Fare Distribution Boxplot
* Age vs Fare Scatterplot
* Correlation Heatmap

---

# Conclusion

This project demonstrates basic to intermediate Exploratory Data Analysis techniques using the Titanic dataset. It helps understand how visualization and feature engineering can reveal important patterns in data.

---

# Author

## Rahul Prajapat
