# ElevateLabs_Task5

The cleaned dataset contains 891 rows and 11 columns, with all missing values handled and the Cabin column removed due to its sparsity.

## Cleaning Summary
Age: 177 missing → filled with median age = 28.0

Embarked: 2 missing → filled with most common port = 'S'

Cabin: Dropped due to over 77% missing

Dataset now has no missing values

Key Statistics

Survival Rates:

Overall Survival Rate: ~38.4%

By Sex: Female 74.2% | Male 18.9%

By Class: 1st - 62.9% | 2nd - 47.3% | 3rd - 24.2%

Age:

Mean: 29.4 years | Median: 28 | Min: 0.42 | Max: 80

Fare:
Mean: $32.20 | Median: $14.45 | Max: $512.33

Wide variation — useful for economic status estimation

# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs an in-depth exploratory data analysis (EDA) on the famous Titanic dataset, revealing insights into passenger demographics, survival rates, and the effect of various features on survival outcomes.

## Project Structure

├── Titanic_EDA.ipynb # Main Jupyter Notebook
├── Titanic_EDA_Summary.md # Summary report of analysis
├── README.md # This file
└── data/ # (Optional) Directory for raw/cleaned data


---

## EDA Objectives

- Understand dataset structure and quality
- Clean and preprocess missing or inconsistent data
- Perform univariate and bivariate analysis
- Visualize relationships using matplotlib/seaborn
- Identify key factors influencing survival

---

##  Data Cleaning Techniques

- **Missing Values**: Imputed `Age` with median; filled `Embarked` with mode.
- **Dropped Columns**: Removed or transformed `Cabin` due to high missingness.
- **Outliers**: Transformed `Fare` to normalize skewed data.
- **Encoding**: Converted categorical variables like `Sex` and `Embarked`.

These steps directly impacted the clarity and accuracy of insights during analysis.

---

##  Key Findings

- **Sex**: Females had significantly higher survival rates.
- **Pclass**: First-class passengers were more likely to survive.
- **Age**: Children had higher chances of survival.
- **Fare & Embarkation**: Higher fares and certain embarkation points (like 'C') correlated with better survival.

---

## 📈 Tools & Libraries

- **Python 3**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `nbconvert` (for generating reports)

