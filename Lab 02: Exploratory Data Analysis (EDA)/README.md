# Lab 02: Exploratory Data Analysis (EDA) on the Titanic Dataset

## 📌 **Objective**

The goal of this lab is to perform an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset to:

- Understand the structure and basic features of the dataset.
- Conduct Univariate, Bivariate, and Multivariate Analysis.
- Identify missing values and handle them appropriately.
- Utilize data visualizations to derive meaningful insights.

## 📂 **Dataset Overview**

The lab utilizes the Titanic dataset, which contains information about passengers, including demographics, ticket details, and survival status. Key features include:

- `PassengerId`: Unique ID for each passenger
- `Survived`: Survival indicator (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1st, 2nd, 3rd)
- `Name`: Passenger’s name
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Fare paid for the ticket
- `Cabin`: Cabin number (if available)
- `Embarked`: Port of embarkation (C, Q, S)

## 📊 **Tasks Covered**

### 🔹 **Task 1: Dataset Exploration**

- Examine the dataset structure using `head()`, `info()`, and `describe()`.
- Identify missing values and duplicates.

### 🔹 **Task 2: Numerical Data Analysis**

- Analyze key statistical properties and distributions of numerical columns such as `Age`, `Fare`, and `Parch`.
- Utilize histograms and boxplots for better insights.

### 🔹 **Task 3: Categorical Data Analysis**

- Analyze categorical variables like `Pclass`, `Sex`, and `Embarked`.
- Use count plots and bar charts to visualize distributions.

### 🔹 **Task 4: Survival Analysis**

- Investigate survival rates across different features.
- Compare survival rates by gender, passenger class, and embarkation port.

### 🔹 **Task 5: Correlation and Multivariate Analysis**

- Examine relationships between multiple variables.
- Use heatmaps and pairplots to visualize correlations.

## 📌 **Technologies & Libraries Used**

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

## 🚀 **How to Run the Notebook**

1. Install necessary libraries using:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Run the notebook cells sequentially.

## 📈 **Expected Outcomes**

By the end of this lab, you will have:

- A strong understanding of the Titanic dataset.
- Experience in applying different EDA techniques.
- Insights into survival factors among passengers.
- Improved skills in data visualization and statistical analysis.
## 📊 **Key Outputs (Plots & Visualizations)**
During the analysis, multiple data visualizations were generated, including:

-Histogram & Boxplot of Age → To understand the age distribution and detect outliers.
-Survival Rate by Gender → Visualizing survival differences between males and females.
-Correlation Heatmap → Identifying relationships between numerical variables.
-Passenger Class Distribution → Analyzing the distribution of passengers across different classes.
-Fare Distribution Plot → Examining ticket fare variation.
## 📚 References
-Kaggle Titanic Dataset: https://www.kaggle.com/c/titanic
-Seaborn Documentation: https://seaborn.pydata.org/
-Matplotlib Documentation: https://matplotlib.org/

## 📜 **Conclusion**

EDA is a crucial step in understanding datasets before applying machine learning models. Through visualization and statistical analysis, we can uncover valuable patterns and insights that help in better decision-making.

---
**Habib Ullah** <br>
Undergraduate Computer Engineering Student, UET Taxila.

