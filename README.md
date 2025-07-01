# Task5_ElevateLabs
#  Titanic Dataset - Exploratory Data Analysis (EDA)

##  Objective
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and anomalies that may influence survival during the Titanic disaster. The focus is on statistical summaries and visual insights using Python.

##  Dataset
The project uses the following files from the Titanic dataset:

- `train.csv`: Training dataset with survival labels.
- `test.csv`: Test dataset (not used in this EDA).
- `gender_submission.csv`: Sample submission (not used in EDA).

##  Tools and Libraries
- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

##  EDA Highlights

- Checked data structure and missing values using `.info()`, `.describe()`, and `.isnull().sum()`
- Computed exact counts and percentages for survivors:
  - **Survived:** 342
  - **Not Survived:** 549
- Visualized:
  - Survival by gender
  - Class vs survival
  - Age distribution and survival
  - Correlation heatmap
  - Pairplots of numerical features

##  Key Insights

- **Women** and **children** had higher survival rates.
- **First-class** passengers had the best survival odds.
- **Fare** positively correlates with survival.
- **Males in third class** were most vulnerable.

##  Data Cleaning

- Imputed missing `Age` values with the median.
- Filled missing `Embarked` values with the mode.
- Dropped the `Cabin` column due to high missing values.

##  Deliverables

-  `Task_5.ipynb` — Jupyter Notebook with EDA code and visuals.
-  `Titanic_EDA_Report.pdf` — PDF report (via Overleaf/LaTeX).
-  Plots: `survival_count.png`, `age_distribution.png`, etc.

##  Outcome

This EDA builds foundational understanding for predictive modeling and machine learning by:
- Revealing hidden patterns in the dataset
- Visualizing feature relationships
- Cleaning and preparing data

---
