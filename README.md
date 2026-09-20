# Codveda Technology Data Analytics Internship

## 📊 Data Analytics Projects

This repository contains my completed projects from the **Codveda Technology Data Analytics Internship**.

The projects cover practical work in **data cleaning, data visualization, regression analysis, time-series analysis, predictive modeling, and Power BI dashboard development**.

Throughout the internship, I worked with Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, Jupyter Notebook, and Microsoft Power BI.

---

## 👨‍💻 About the Internship

The Codveda Technology Data Analytics Internship provided hands-on experience with different stages of the data analytics and machine learning workflow.

The work in this repository demonstrates how I:

* Load and inspect datasets
* Clean and preprocess data
* Check missing values and duplicate records
* Standardize categorical data
* Perform exploratory analysis
* Create data visualizations
* Build regression models
* Analyze time-series data
* Build classification models
* Preprocess categorical and numerical features
* Evaluate machine learning models
* Perform hyperparameter tuning
* Analyze feature importance
* Create interactive Power BI dashboards
* Use Power Query and DAX
* Present analytical results through visualizations

---

# 📁 Repository Structure

```text
codvedaprojects/
│
├── Umair-L1-TASK1 Datacleanng and preprocessing/
│   ├── 1) iris.csv
│   ├── umair-L1-Task1-Datacleaningandpreprocessing.ipynb
│   └── README.md
│
├── Umair-L1-TASK 3 Basic Data visualization/
│   ├── 1) iris.csv
│   ├── Umair-L1-Task 3-Basic Data Visualization.ipynb
│   ├── model images/
│   └── README.md
│
├── Umair-L2-TASK 1 Regression Analysis/
│   ├── 4) house Prediction Data Set.csv
│   ├── Umair-L2-TASK1-RegressionAnalysis.ipynb
│   └── README.md
│
├── Umair-L2-TASK-2 TimeSeriesAnalysis/
│   ├── 2) Stock Prices Data Set.csv
│   ├── Umair-Level2-Task2 TimeSeriesAnalysis.ipynb
│   ├── model images/
│   └── README.md
│
├── Umair-Level3-TASK1-Predictive Modeling/
│   ├── churn-bigml-80.csv
│   ├── umair-level3-task1-Predictive Modeling.ipynb
│   ├── images visulaizations/
│   └── README.md
│
└── Umair-Level3-TASK2-Building Dashboards with Power BI/
    ├── 2) Stock Prices Data Set(4).csv
    ├── dashboard images/
    └── README.md
```

---

# 🟢 Level 1 — Basic Data Analytics

## Task 1 — Data Cleaning and Preprocessing

**Folder:** `Umair-L1-TASK1 Datacleanng and preprocessing`

### Dataset

The project uses the **Iris dataset**.

### What I Did

The main objective was to clean and prepare the dataset for further analysis.

The workflow included:

1. Imported the required Python libraries.
2. Loaded the Iris dataset using Pandas.
3. Inspected the dataset using:

   * `df.info()`
   * `df.shape`
   * `df.head()`
   * `df.dtypes`
4. Checked for missing values.
5. Calculated missing-value percentages.
6. Identified duplicate rows.
7. Removed duplicate records.
8. Checked unique values in the `species` column.
9. Standardized categorical values by:

   * Removing leading and trailing spaces
   * Converting text to lowercase
10. Converted the `species` column to a categorical data type.
11. Verified the cleaned dataset and final data types.

### Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Task 3 — Basic Data Visualization

**Folder:** `Umair-L1-TASK 3 Basic Data visualization`

### Dataset

The project uses the **Iris flower dataset**.

### What I Did

I performed basic data exploration and created visualizations to communicate patterns in the dataset.

The visualizations included:

* **Bar Chart** — Number of Iris samples by species
* **Scatter Plot** — Petal length vs. petal width by species
* **Line Chart** — Variation in sepal length across observations

I also:

* Inspected the dataset structure
* Checked column names and data types
* Saved generated visualizations as image files
* Documented observations from the charts

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* OS

### Output Visualizations

```text
species_bar_plot.png
petal_length_vs_width.png
sepal_length_line_chart.png
```

---

# 🟡 Level 2 — Intermediate Data Analytics

## Task 1 — Regression Analysis

**Folder:** `Umair-L2-TASK 1 Regression Analysis`

### Dataset

The project uses the house prediction dataset available in the repository as:

```text
4) house Prediction Data Set.csv
```

### Objective

The project applies a **multiple linear regression** approach to predict house values using property and neighborhood-related features.

### What I Did

The analysis follows a regression workflow including:

1. Loading the dataset
2. Preparing the data
3. Separating features and target values
4. Splitting the data into training and testing sets
5. Building a Linear Regression model
6. Evaluating the model using:

   * R² score
   * Mean Squared Error
7. Reviewing regression coefficients
8. Considering potential improvements to the model

### Key Concepts

* Train/Test Split
* Linear Regression
* Regression Coefficients
* R² Score
* Mean Squared Error
* Model Evaluation

### Tools & Libraries

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

---

## Task 2 — Time Series Analysis

**Folder:** `Umair-L2-TASK-2 TimeSeriesAnalysis`

### Dataset

The project uses historical stock-price data and focuses on **Apple Inc. (AAPL)**.

Dataset:

2) Stock Prices Data Set.csv

### Objective

The purpose of the project was to analyze historical stock prices and explore trends, seasonal patterns, residual behavior, and moving-average smoothing.

### What I Did

The workflow included:

1. Loading historical stock-price data
2. Cleaning and preparing the data
3. Examining closing prices over time
4. Performing exploratory analysis
5. Analyzing time-series patterns
6. Performing time-series decomposition
7. Visualizing the analysis
8. Examining moving-average behavior

### Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Statsmodels
* Jupyter Notebook

### Note

The analysis is focused on AAPL and is intended as an educational data-analysis project rather than investment advice.

---

# 🔴 Level 3 — Advanced Data Analytics

## Task 1 — Predictive Modeling: Customer Churn Classification

**Folder:** `Umair-Level3-TASK1-Predictive Modeling`

### Dataset

The project uses:

```text
churn-bigml-80.csv
```

### Dataset Information

* **Rows:** 2,666
* **Columns:** 20
* **Target Variable:** `Churn`
* **Target Classes:** `True` and `False`

### Objective

The objective was to build machine learning classification models that predict customer churn.

### What I Did

The project followed a complete machine learning workflow:
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Quality Checks
   ↓
Feature / Target Separation
   ↓
Categorical Encoding
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Decision Tree
   ↓
Logistic Regression
   ↓
Random Forest
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
GridSearchCV
   ↓
Feature Importance
   ↓
Conclusion

### Data Preprocessing

I used:

* `StandardScaler`
* `OneHotEncoder`
* `ColumnTransformer`
* `Pipeline`

Categorical variables were encoded, while numerical features were scaled as part of the preprocessing workflow.

### Machine Learning Models

The following classification models were implemented:

#### Decision Tree Classifier

Used as one of the baseline classification models for predicting customer churn.

#### Logistic Regression

Used as a linear classification model and evaluated alongside the tree-based models.

#### Random Forest Classifier

Used as an ensemble classification model for churn prediction and feature-importance analysis.

### Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### Hyperparameter Tuning

`GridSearchCV` was used to tune the Random Forest model.

The workflow included testing different combinations of Random Forest parameters and evaluating the tuned model.

### Feature Importance

Feature importance was examined to understand which variables contributed most to the Random Forest model's predictions.

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

### Scikit-learn Components
train_test_split
StandardScaler
OneHotEncoder
ColumnTransformer
Pipeline
DecisionTreeClassifier
LogisticRegression
RandomForestClassifier
GridSearchCV
accuracy_score
precision_score
recall_score
f1_score
confusion_matrix
ConfusionMatrixDisplay

# 📊 Level 3 Task 2 — Power BI Dashboard

**Folder:** `Umair-Level3-TASK2-Building Dashboards with Power BI`

## Stock Market Analysis Dashboard

### Tool

**Microsoft Power BI**

### Dataset

The dashboard uses historical stock-price data stored as:
2) Stock Prices Data Set(4).csv

### Objective

The objective was to build an interactive stock market analysis dashboard for exploring stock-price trends, stock performance, and trading volume.

### What I Did

The project workflow included:

1. Imported the CSV dataset into Power BI.
2. Cleaned and transformed the data using Power Query.
3. Checked and assigned appropriate data types.
4. Created DAX measures.
5. Created KPI cards.
6. Built stock-price trend visualizations.
7. Analyzed average closing prices by stock.
8. Analyzed trading volume.
9. Added interactive slicers.
10. Designed and formatted the dashboard.

### Data Types Used

The project included fields such as:
symbol → Text
date → Date
open → Decimal Number
high → Decimal Number
low → Decimal Number
close → Decimal Number
volume → Whole Number


### Dashboard Components

The dashboard includes analysis such as:

* Average Close
* Highest Price
* Lowest Price
* Total Trading Volume
* Stock Price Trends
* Average Closing Price by Stock
* Trading Volume Analysis
* Stock Symbol Slicer

### Power BI Technologies

* Microsoft Power BI Desktop
* Power Query
* DAX
* Data Visualization
* Interactive Filters
* Slicers
* KPI Cards

# 🛠️ Tools & Technologies

## Programming

* Python

## Data Analysis

* Pandas
* NumPy

## Data Visualization

* Matplotlib
* Seaborn

## Machine Learning

* Scikit-learn

## Time Series

* Statsmodels

## Business Intelligence

* Microsoft Power BI
* Power Query
* DAX

## Development Environment

* Jupyter Notebook
* Visual Studio Code

---

# 📚 Python Libraries

The projects in this repository use libraries including:

python
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels

The exact libraries used vary by project.

🔄 Overall Data Analytics Workflow

Across the projects, I worked through different stages of the data analytics process:

Data Collection
      ↓
Data Loading
      ↓
Data Inspection
      ↓
Data Cleaning
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Data Visualization
      ↓
Statistical / Time-Series Analysis
      ↓
Machine Learning
      ↓
Model Evaluation
      ↓
Dashboard Development
      ↓
Insights & Reporting
```

---

# 🧠 Skills Demonstrated

Through these projects, I developed practical experience with:

### Data Preparation

* Data loading
* Data inspection
* Missing-value checking
* Duplicate detection
* Duplicate removal
* Categorical data cleaning
* Data type conversion
* Feature preprocessing

### Data Analysis

* Exploratory data analysis
* Descriptive analysis
* Correlation and relationships
* Time-series analysis
* Trend analysis
* Moving averages
* Time-series decomposition

### Data Visualization

* Bar charts
* Line charts
* Scatter plots
* Comparative visualizations
* Model-related visualizations
* Dashboard visualizations

### Machine Learning

* Train/test splitting
* Feature encoding
* Feature scaling
* Classification
* Regression
* Decision Trees
* Logistic Regression
* Random Forest
* Hyperparameter tuning
* Model evaluation
* Feature importance

### Business Intelligence

* Power BI
* Power Query
* DAX
* KPI development
* Interactive slicers
* Dashboard design
* Data visualization


# 📈 Project Coverage

| Level   | Task   | Project                            | Main Technologies                       |
| ------- | ------ | ---------------------------------- | --------------------------------------- |
| Level 1 | Task 1 | Data Cleaning & Preprocessing      | Python, Pandas, NumPy                   |
| Level 1 | Task 3 | Basic Data Visualization           | Python, Matplotlib, Seaborn             |
| Level 2 | Task 1 | Regression Analysis                | Python, Pandas, Scikit-learn            |
| Level 2 | Task 2 | Time Series Analysis               | Python, Pandas, Statsmodels, Matplotlib |
| Level 3 | Task 1 | Customer Churn Predictive Modeling | Python, Pandas, Scikit-learn            |
| Level 3 | Task 2 | Stock Market Power BI Dashboard    | Power BI, Power Query, DAX              |


# 📂 Project Organization

Each completed task is maintained in its own folder.

Each project folder may contain:

* Dataset
* Jupyter Notebook
* Visualization images
* Dashboard images
* Task-specific README
* Other supporting project files

This structure keeps each internship task organized and makes individual projects easier to review.

# ▶️ How to Use This Repository

### 1. Clone the repository

```bash
git clone https://github.com/umairr-95/codvedaprojects.git
```

### 2. Open the project

Navigate into the repository:

```bash
cd codvedaprojects
```

### 3. Open a project folder

Choose the task you want to review.

For Python projects, open the corresponding `.ipynb` notebook using:

* Jupyter Notebook
* JupyterLab
* Visual Studio Code

### 4. Install the required Python libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

### 5. Run the notebook

Open the relevant notebook and execute the cells sequentially.

For the Power BI project, open the dataset in **Microsoft Power BI Desktop** and review the dashboard and supporting images included in the project folder.

---

# 🎯 Internship Learning Outcomes

This internship allowed me to gain hands-on experience across multiple areas of data analytics.

I worked with:

* Data cleaning
* Data preprocessing
* Data visualization
* Regression analysis
* Time-series analysis
* Classification
* Machine learning model evaluation
* Hyperparameter tuning
* Feature importance
* Power BI
* Power Query
* DAX
* Interactive dashboard development

The projects helped me understand how raw datasets can be transformed into analytical insights, predictive models, and interactive business intelligence dashboards.

---

# 📌 Repository Status

This repository contains the completed projects currently included in the repository.

### Completed

* ✅ Level 1 — Task 1: Data Cleaning and Preprocessing
* ✅ Level 1 — Task 3: Basic Data Visualization
* ✅ Level 2 — Task 1: Regression Analysis
* ✅ Level 2 — Task 2: Time Series Analysis
* ✅ Level 3 — Task 1: Predictive Modeling
* ✅ Level 3 — Task 2: Power BI Dashboard

Tasks not listed above are not represented as completed projects in this repository.

---

# 👤 Author

**Umair Akbar Mohammed**

Data Analytics Intern
Python | Data Analytics | Machine Learning | Power BI

---

## 🔗 Repository

This repository contains my Codveda Technology Data Analytics Internship projects and supporting files.

**GitHub:** `umairr-95/codvedaprojects`

---

## 📄 Internship Project

This repository was created to document my practical work and learning throughout the **Codveda Technology Data Analytics Internship**.
