# Salary Prediction for Tech World - A Udacity Project
This is a repository that includes the details of the project that predicts Salary in "Stack Overflow Annual Developer Survey" data

# Stack Overflow 2024 — Salary Prediction (Manual CSV)

This project uses the "2024 Stack Overflow Developer Survey" and a simple ML pipeline to predict annual compensation (Salary).

## Data
- Official site (choose **2024 → Download Full Data Set (CSV)**): https://survey.stackoverflow.co/

Update the file path in the script if needed.

## Acknowledgments:
The dataset used in this project is sourced from the Stack Overflow Developer Survey, which provides valuable insights into developers' experiences, skills, and salaries.

## For further reading, 
Check out the blog post: [Predicting Developer Salaries: What Matters Most](https://medium.com/@durmusmuratt/a-detailed-insight-for-salaries-in-tech-world-a929053bbdd5)

## How to run
1) Download the CSV.
2) Open `Udacity_Project_Salary_Pred.ipynb`.
3) Edit the line `CSV_PATH = '/survey_results_public.csv.csv'` and run the code

## Technology Requirements
- pandas, numpy, scikit-learn, matplotlib, seaborn

## Notes
- All columns are included (one-hot encoding for categoricals).
- RandomForestRegressor for easy feature importances.
