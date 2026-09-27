# Titanic Exploratory Data Analysis (EDA)

A beginner-friendly Exploratory Data Analysis project using Python and Pandas on the classic Titanic dataset.

## Objectives
- Load and inspect the dataset with `head()`, `info()`, and `describe()`
- Identify and handle missing values
- Detect and remove duplicate records
- Perform grouping and aggregation
- Explore survival patterns using Pandas, Matplotlib, and Seaborn
- Generate data-driven statistical insights

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
```text
Titanic_EDA_Project/
├── data/
│   └── README.md
├── notebooks/
│   └── Titanic_EDA.ipynb
├── src/
│   └── eda_analysis.py
├── visualizations/
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset
The notebook downloads the Titanic CSV from a public GitHub mirror when executed, so the repository does not need to contain a large dataset file.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Titanic_EDA.ipynb
```

You can also run:
```bash
python src/eda_analysis.py
```

## Main Analysis
1. Data loading
2. DataFrame inspection
3. Missing-value analysis and treatment
4. Duplicate detection/removal
5. Descriptive statistics
6. Grouping and aggregation
7. Survival analysis by gender and passenger class
8. Age and fare distributions
9. Correlation analysis
10. Key findings

## Expected Learning Outcome
This project demonstrates practical Pandas skills and exploratory data-cleaning techniques suitable for a beginner data-analysis portfolio or internship submission.
