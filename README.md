# Data-Science-Salary-Prediction(Regression Problem)

## Problem Statement:
To perform exploratory data analysis to find important insights into salaries of data science professionals.

## Data Collection:
The dataset for this project is collected from [Kaggle](https://www.kaggle.com/datasets/saurabhshahane/data-science-jobs-salaries) and consists of 12 columns and 607 rows. 

### Data Science Job Salaries Dataset Columns:

1. **work_year**: The year the salary was paid.

2. **experience_level**: The experience level in the job during the year.

3. **employment_type**: The type of employment for the role.

4. **job_title**: The role worked in during the year.

5. **salary**: The total gross salary amount paid.

6. **salary_currency**: The currency of the salary paid as an ISO 4217 currency code.

7. **salary_in_usd**: The salary in USD.

8. **employee_residence**: Employee's primary country of residence during the work year as an ISO 3166 country code.

9. **remote_ratio**: The overall amount of work done remotely.

10. **company_location**: The country of the employer's main office or contracting branch.

11. **company_size** : The median number of people that worked for the company during the year.

12. **Updated_Job_Title** :  Updated version of the job title for certain entries in the dataset.

    

## Project Structure:
The project directory is organized as follows:

- **data**: Contains datasets used in the project.
  - **ds_cleaned.csv**: The cleaned dataset.
  - **ds_feature_eng**: Folder for feature-engineered datasets.
  - **ds_salaries.csv**: Additional dataset related to salaries.

- **models**: Stores trained machine learning models.
  - **model.pkl**: The saved model.

- **DATA CLEANING.ipynb**: Jupyter Notebook for data cleaning.
- **EDA - DATA SCIENCE SALARY PREDICTION .ipynb**: Notebook for exploratory data analysis.
- **FEATURE ENGINEERING.ipynb**: Notebook for feature engineering.
- **MODEL TRAINING.ipynb**: Notebook for model training.
