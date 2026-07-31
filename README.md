# Banking Customer Data Analysis using Python & Power BI

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a banking customer dataset using **Python** and developing an interactive **Power BI dashboard** to visualize key business insights.

The objective of this project is to understand customer demographics, banking behaviour, financial characteristics, and relationships among different variables through statistical analysis and interactive visualizations.

---

## Project Objectives

- Explore the banking customer dataset.
- Perform data understanding and descriptive analysis.
- Create new features to improve analysis.
- Analyze categorical and numerical variables.
- Perform univariate and bivariate analysis.
- Identify relationships among financial variables.
- Build an interactive Power BI dashboard for business insights.

---

## Dataset

The dataset contains information related to banking customers including:

- Age
- Gender
- Location
- Nationality
- Occupation
- Estimated Income
- Credit Card Balance
- Bank Deposits
- Bank Loans
- Savings Account
- Checking Account
- Foreign Currency Account
- Business Lending
- Loyalty Classification
- Risk Weighting
- Properties Owned
- Credit Cards Owned

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL (PostgreSQL)
- SQLAlchemy
- Jupyter Notebook
- Power BI

---

# Project Workflow

### 1. Data Import

The banking data was imported from a PostgreSQL database into a Pandas DataFrame using SQLAlchemy.

---

### 2. Data Exploration

The following steps were performed:

- Dataset Preview
- Dataset Shape
- Dataset Information
- Missing Value Inspection
- Descriptive Statistics

---

### 3. Feature Engineering

A new feature named **Income Band** was created by categorizing estimated income into:

- Low
- Medium
- High

This feature was later used during exploratory analysis.

---

# Exploratory Data Analysis (EDA)

## Categorical Feature Analysis

The project analyzes the distribution of categorical variables including:

- Gender
- Nationality
- Occupation
- Loyalty Classification
- Fee Structure
- Risk Weighting
- Income Band
- Credit Cards Owned
- Properties Owned

The frequency distribution of each category helps understand customer segmentation.

---

## Univariate Analysis

Univariate analysis was performed to understand the individual distribution of different categorical features using count plots.

The analysis highlights:

- Customer demographics
- Banking preferences
- Loyalty categories
- Occupation distribution
- Income groups

---

## Bivariate Analysis

Bivariate analysis was performed to study relationships between different customer attributes.

The notebook compares multiple customer characteristics with **Nationality** to identify demographic patterns.

These visualizations help identify:

- Customer distribution across occupations
- Loyalty variation
- Fee structure differences
- Income categories
- Property ownership trends

---

## Numerical Feature Analysis

The project also analyzes numerical variables through histograms.

Variables include:

- Age
- Estimated Income
- Superannuation Savings
- Credit Card Balance
- Bank Loans
- Bank Deposits
- Checking Accounts
- Saving Accounts
- Foreign Currency Accounts
- Business Lending

This analysis helps understand:

- Distribution
- Skewness
- Spread
- Outliers

---

## Correlation Analysis

A correlation heatmap was generated for numerical variables to understand relationships among financial features.

This helps identify positively and negatively correlated variables useful for further predictive analysis.

---

# Power BI Dashboard

An interactive dashboard was created in **Power BI** to summarize important banking insights.

The dashboard enables users to:

- Explore customer demographics
- Analyze financial indicators
- Filter customer segments
- Visualize banking behaviour
- Support business decision making

---

# Repository Structure

```
Banking/
│
├── data/
│   └── Banking_data.csv
│
├── notebooks/
│   └── Banking.ipynb
│
├── power_bi/
│   └── banking_cv.pbix
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# How to Run

1. Clone the repository.

```
git clone <repository-url>
```

2. Install dependencies.

```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```
jupyter notebook
```

4. Run all notebook cells.

5. Open the Power BI dashboard using Power BI Desktop.

---

# Future Improvements

- Handle missing values using advanced imputation techniques.
- Perform outlier detection and treatment.
- Develop predictive machine learning models.
- Create customer segmentation using clustering.
- Build customer churn prediction models.
- Deploy the dashboard on Power BI Service.

---

# Author

**Sanskar**

Instrumentation & Control Engineering  
Netaji Subhas University of Technology (NSUT)

---

## If you found this project useful, consider giving it a ⭐ on GitHub.