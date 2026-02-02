# Udacity_Project_Salary_Pred
This is a repository that includes the details of the project that predicts Salary in "Stack Overflow Annual Developer Survey" data

# Stack Overflow 2024 — Full Data Salary Prediction (Manual CSV)

This project uses the "2024 Stack Overflow Developer Survey" and a simple ML pipeline to predict annual compensation (Salary).

## Data
- Official site (choose **2024 → Download Full Data Set (CSV)**): https://survey.stackoverflow.co/

## How to run
1) Download the CSV.
2) Open `Udacity_Project_Salary_Pred.ipynb`.
3) Edit the line `CSV_PATH = '../data/your_file.csv'` and run the code

## Technology Requirements
- pandas, numpy, scikit-learn, matplotlib, seaborn

## Outputs
- `images/` → plots (target histogram, missingness, feature importances)
- `outputs/` → metrics (`results_auto.md`) and top-20 features CSV

## Notes
- All columns are included (one-hot encoding for categoricals).
- RandomForestRegressor for easy feature importances.
