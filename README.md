# Prodigy InfoTech Data Science Internship - Task 2

## 📌 Project Overview
This repository contains my solution for **Task 2** of the Data Science Internship at **Prodigy InfoTech**. The goal of this task was to perform comprehensive data cleaning and **Exploratory Data Analysis (EDA)** to identify trends and patterns within a dataset.

## 📊 Task Description
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the **Titanic dataset from Kaggle**. Explore the relationships between variables and identify patterns and trends in the data.

## 🗃️ Dataset
I utilized the **Titanic Dataset** from Kaggle, which includes historical passenger information such as age, gender, ticket class, and survival outcomes.
* **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

### 📖 Data Dictionary
| Variable | Definition | Key |
| :--- | :--- | :--- |
| **survival** | Survival | 0 = No, 1 = Yes |
| **pclass** | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| **sex** | Sex | |
| **Age** | Age in years | |
| **sibsp** | # of siblings / spouses aboard | |
| **parch** | # of parents / children aboard | |
| **ticket** | Ticket number | |
| **fare** | Passenger fare | |
| **cabin** | Cabin number | |
| **embarked** | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |

### 📝 Variable Notes
* **pclass:** A proxy for socio-economic status (SES) (1st = Upper, 2nd = Middle, 3rd = Lower).
* **age:** Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5.
* **sibsp:** Defines family relations as Sibling (brother, sister, stepbrother, stepsister) or Spouse (husband, wife).
* **parch:** Defines family relations as Parent (mother, father) or Child (daughter, son, stepdaughter, stepson). Note: Children traveling only with a nanny have parch=0.

## 🛠️ Key Steps Involved
1. **Data Cleaning:**
   - Handled missing values in critical columns such as 'Age', 'Cabin', and 'Embarked'.
   - Filtered and preprocessed the data to ensure accuracy for statistical analysis.
2. **Exploratory Data Analysis (EDA):**
   - Investigated the relationships between socio-economic status (Pclass), gender, and survival rates.
   - Analyzed the distribution of numerical variables like age and fare prices.
3. **Visualization:**
   - Used **Seaborn** heatmaps to identify correlations between different features.
   - Created count plots and histograms to visualize the demographic factors influencing survival.



## 🚀 Technologies Used
- **Python**
- **Pandas** (Data Cleaning & Manipulation)
- **Matplotlib & Seaborn** (Statistical Visualization)
- **Google Colab** (Development Environment)

## 💡 Insights
* **Socio-Economic Impact:** The analysis revealed a strong correlation between passenger class and survival probability, with first-class passengers having higher survival rates.
* **Demographic Trends:** Visualizations confirmed that age and gender were significant predictors, reflecting the historical "women and children first" protocol.

---
