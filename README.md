# Titanic EDA Notebook

Exploratory data analysis of the Titanic dataset to understand 
what factors drove passenger survival.

## What I Did
- Audited and cleaned missing values with justified strategies
- Analyzed survival patterns across gender, class, and age
- Visualized findings with Seaborn and Matplotlib
- Summarized insights in a structured findings section

## Key Finding
Gender and passenger class were the strongest survival predictors.
Women (74%) and 1st-class passengers (63%) survived at far higher rates
than men (19%) and 3rd-class passengers (24%).

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook titanic_eda.ipynb
```

## Dataset
Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data).  
Place `train.csv` inside the `data/` folder before running.

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter