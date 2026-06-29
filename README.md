# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, identify missing values, analyze passenger demographics, and understand the factors influencing survival.

## Dataset

- **Dataset:** Titanic Dataset
- **Rows:** 891
- **Columns:** 12

## Objectives

- Inspect and understand the dataset
- Identify missing values and duplicates
- Perform statistical analysis
- Conduct univariate analysis
- Conduct bivariate analysis
- Analyze feature correlations
- Summarize key insights

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
EDA Titanic Analysis/
│
├── EDA.ipynb
├── titanic.csv
├── README.md
├── requirements.txt
└── images/
    ├── age_distribution.png
    ├── gender_distribution.png
    ├── passenger_class.png
    ├── embarked_distribution.png
    ├── age_boxplot.png
    ├── fare_boxplot.png
    ├── survival_by_gender.png
    ├── survival_by_class.png
    ├── survival_by_embarked.png
    ├── age_vs_survival.png
    ├── fare_vs_survival.png
    └── correlation_heatmap.png
```

## Key Insights

- The dataset contains 891 passenger records and 12 features.
- The `Cabin` column contains a high percentage of missing values.
- Most passengers were between 20 and 40 years old.
- Male passengers outnumbered female passengers.
- Third-class passengers represented the largest passenger group.
- Female passengers had a significantly higher survival rate than males.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Passengers who paid higher fares generally had better survival rates.
- No duplicate records were found.

## Conclusion

The exploratory data analysis revealed meaningful relationships between passenger demographics and survival outcomes. The project demonstrates how statistical summaries and visualizations can uncover valuable insights before predictive modeling.
