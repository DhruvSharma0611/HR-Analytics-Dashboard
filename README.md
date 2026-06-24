# 📊 HR Analytics Dashboard

An interactive HR analytics dashboard built in Tableau, powered by a synthetic dataset of 8,950 employee records.

## Dashboard features
- Headcount overview (active vs. terminated)
- Salary analysis by department, education & gender
- Performance rating distribution
- Hiring trends by year (2015–2024)
- Geographic map across 8 US states

## Tech stack
- Tableau Desktop
- Python 3, Pandas, NumPy, Faker

## Dataset
8,950 synthetic employee records with 14 fields including Department, Salary, Education Level, Performance Rating, Hire/Termination Date, and Location.

## How to run
```bash
pip install pandas numpy faker
python generate_data.py
```
Then open `HR_Dashboard.twbx` in Tableau Desktop.
