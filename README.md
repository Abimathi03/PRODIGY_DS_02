# 🚢 Titanic Dataset: Data Cleaning & Exploratory Data Analysis (EDA)

This project involves performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The goal is to explore relationships between variables and identify patterns and trends in the data.

---

## 📂 Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Findings](#key-findings)

---

## 📌 Overview

The Titanic dataset provides information on the passengers aboard the Titanic, including details such as age, gender, class, and survival status. This project focuses on cleaning the dataset and performing EDA to uncover insights about the factors influencing survival.

---

## 📝 Dataset Description

The dataset comprises the following features:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger's name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Jupyter Notebook**: Interactive computing environment

---

## 🚀 Usage

1. Open the Jupyter Notebook
2. Open the file
3. Run the cells

---

## 🧹 Data Cleaning

The data cleaning process includes:

1. **Handling Missing Values**:

- Replacing missing values in the 'Age' column with the median age.
- Filling missing values in the 'Embarked' column with the mode.
- Dropping the 'Cabin' column due to a high number of missing values.

2. **Encoding Categorical Variables**:

- Converting 'Sex' and 'Embarked' columns into numerical format using label encoding.

3. **Removing Unnecessary Columns**:

- Dropping columns like 'Name', 'Ticket', and 'PassengerId' that are not essential for analysis.

---

## 📊 Exploratory Data Analysis (EDA)

The EDA process involves:

1. **Univariate Analysis**:

- Distribution plots for 'Age' and 'Fare'.
- Count plots for 'Survived', 'Pclass', 'Sex', and 'Embarked'.

2. **Bivariate Analysis**:

- Survival rate by gender.
- Survival rate by passenger class.
- Survival rate by embarkation point.

3. **Multivariate Analysis**:

- Heatmap to visualize correlations between numerical features.

---

## 🔍 Key Findings

- **Gender**: Females had a higher survival rate compared to males.
- **Passenger Class**: Passengers in 1st class had a higher chance of survival.
- **Embarkation Point**: Passengers who embarked from Cherbourg had a higher survival rate.
