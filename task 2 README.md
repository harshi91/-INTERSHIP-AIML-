# 🧭 Exploratory Data Analysis (EDA) — Titanic Dataset

## 📘 Objective
The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand data distribution, identify missing values, detect outliers, visualize relationships, and draw meaningful insights that can guide predictive modeling.

---

## 🛠️ Tools & Libraries Used
- **Pandas** → Data manipulation and cleaning  
- **NumPy** → Numerical computations  
- **Matplotlib** → Basic plotting and visualization  
- **Seaborn** → Advanced statistical visualizations  
- **Plotly Express** → Interactive visualizations  

---

## 📦 Dataset
**Dataset:** [Titanic Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
**File:** `titanic.csv`

### **Description**
The Titanic dataset contains details about passengers on the Titanic ship, including whether they survived or not.  
It’s one of the most popular datasets for data analysis and classification problems.

| Feature | Description |
|----------|-------------|
| PassengerId | Unique ID for each passenger |
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name | Passenger name |
| Sex | Gender |
| Age | Age of passenger |
| SibSp | # of siblings/spouses aboard |
| Parch | # of parents/children aboard |
| Fare | Ticket fare |
| Embarked | Port of embarkation |

---

## 🚀 Steps Performed

### 1️⃣ Data Loading & Overview
- Imported required libraries (`pandas`, `numpy`, etc.)
- Loaded dataset using `pd.read_csv()`
- Displayed first few records with `df.head()`

### 2️⃣ Data Summary
- Used `df.info()` to check data types and missing values  
- Used `df.describe()` for summary statistics  
- Identified missing columns (`Age`, `Cabin`, `Embarked`)

### 3️⃣ Data Visualization
#### 🔹 Univariate Analysis
- **Histograms:** Show distribution of numerical columns  
- **Boxplots:** Detect outliers and understand spread  

#### 🔹 Bivariate Analysis
- **Correlation Matrix:** Identified feature relationships  
- **Pairplot:** Displayed relationships among `Age`, `Fare`, `Pclass`, and `Survived`

#### 🔹 Categorical Analysis
- **Countplots:** Visualized survival by gender and class  
- **Plotly Scatter:** Interactive plot for `Age` vs `Fare` colored by survival  

---

## 📊 Key Visualizations
| Visualization | Purpose |
|----------------|----------|
| Histogram | Shows distribution of numeric data |
| Boxplot | Detects outliers |
| Heatmap | Displays correlations |
| Pairplot | Shows pairwise relationships |
| Countplot | Visualizes categorical distributions |
| Plotly Scatter | Interactive survival patterns |

---

## 🧠 Insights & Observations

| Observation | Inference |
|--------------|------------|
| Missing values in `Age`, `Cabin`, `Embarked` | Require imputation or removal |
| Females had higher survival rate | Gender is an important predictor |
| 1st class passengers survived more | Socioeconomic status influenced survival |
| High `Fare` values show outliers | Should be normalized or capped |
| Weak numeric correlations | Combine or engineer new features |

---

## 🎯 Learning Outcomes
- Gained hands-on experience in **data cleaning and visualization**
- Learned to interpret **descriptive statistics**
- Understood **feature relationships and outliers**
- Practiced using **Matplotlib, Seaborn, and Plotly** for data storytelling

---
