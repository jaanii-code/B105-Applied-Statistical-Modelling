# An Empirical Investigation of Customer Churn Determinants in Telecommunications

## B105 Applied Statistical Modelling

**Student:** Jahanvi
**Module:** B105 Applied Statistical Modelling
**Project Type:** Individual Project

---

## 1. Project Overview

This project investigates customer churn in the telecommunications sector using statistical modelling techniques. The analysis focuses on identifying relationships between customer characteristics, service features, contract arrangements, monthly charges, tenure, and customer churn.

The objective is to apply appropriate descriptive and inferential statistical methods to the selected dataset and use the resulting evidence to address the defined business questions.

---

## 2. Business Problem

Customer churn represents an important business issue for telecommunications providers because the loss of subscribers can affect recurring revenue and customer retention.

This project examines customer-level data to identify statistical relationships associated with churn. The findings are used to support evidence-based interpretation of customer retention patterns.

---

## 3. Dataset

The analysis uses the **Telco Customer Churn** dataset.

The dataset contains customer-level information relating to telecommunications services, customer characteristics, account information, contract arrangements, tenure, monthly charges, and churn status.

**Dataset source:** Kaggle – Blastchar

**Dataset URL:**
https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data

The analysis uses selected variables relevant to the research questions and statistical objectives.

---

## 4. Research Questions

The analysis addresses the following research questions:

1. Do churned customers pay significantly higher monthly charges than retained customers?
2. Is there a significant relationship between contract type and customer churn?
3. Does average customer tenure differ across different contract lengths?
4. How do selected customer and service characteristics collectively relate to customer churn probability?

---

## 5. Statistical Methodology

The project follows a structured statistical analysis workflow consisting of data preparation, exploratory analysis, descriptive statistics, bivariate analysis, hypothesis testing, and multivariate modelling.

The statistical techniques implemented include:

* Descriptive statistics
* Exploratory data analysis
* Mann-Whitney U test
* Chi-square test of independence
* One-way ANOVA
* Tukey post-hoc analysis
* Multiple logistic regression
* Statistical assumption validation
* Effect-size and confidence-interval interpretation

The selection of statistical methods is based on the characteristics of the variables and the assumptions associated with each statistical procedure.

---

## 6. Data Preparation

The analysis begins by importing the original dataset and selecting the variables required for the research questions.

The preprocessing workflow includes:

* Selecting relevant variables
* Checking for missing values
* Removing incomplete observations where applicable
* Converting categorical variables into factors
* Preparing variables for statistical analysis
* Creating the binary churn outcome required for logistic regression

All data preparation and statistical analysis procedures are documented in the accompanying Jupyter notebook.

---

## 7. Repository Contents

```text
B105-Applied-Statistical-Modelling/
│
├── README.md
│
├── Data_Analysis.ipynb
│
├── data/
│   └── README.md
│
├── results/
│   ├── univariate_numeric_summary.csv
│   ├── univariate_categorical_summary.csv
│   ├── bivariate_numeric_tests.csv
│   ├── bivariate_categorical_tests.csv
│   ├── h3_anova_results.csv
│   ├── h3_contract_tenure_group_means.csv
│   ├── h3_tukey_posthoc_results.csv
│   └── h4_logistic_regression_results.csv
│
└── figures/
    ├── h1_monthly_charges_boxplot.png
    └── h2_contract_churn_barchart.png
```

---

## 8. Main Analysis File

### `Data_Analysis.ipynb`

This notebook contains the implementation of the statistical analysis, including:

* Dataset import
* Data inspection
* Data cleaning
* Variable preparation
* Descriptive analysis
* Exploratory analysis
* Bivariate statistical testing
* Hypothesis testing
* ANOVA and post-hoc analysis
* Logistic regression
* Statistical outputs and visualisations

The notebook should be executed sequentially to reproduce the analysis.

---

## 9. Results

The `results/` directory contains the statistical outputs generated during the analysis.

These files provide supporting evidence for the descriptive, bivariate, ANOVA, post-hoc, and logistic-regression analyses presented in the report.

The `figures/` directory contains visualisations generated during the analysis.

---

## 10. Software and Packages

The analysis was implemented using **R within a Jupyter Notebook**.

The main R packages used include:

* `readxl`
* `dplyr`
* `tidyr`
* `ggplot2`
* `car`
* `vcd`

---

