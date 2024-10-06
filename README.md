# Predicting Student Dropout and Academic Success

## Project Overview
This project analyzes student data to predict academic success and dropout rates based on demographic, socio-economic, and academic factors. We use Python's data science libraries such as pandas, numpy, and scipy to perform descriptive statistics, data cleaning, and visualization. We further develop machine learning models to predict student success based on various features.

## Dataset
The dataset was obtained from Kaggle: "Predict Students' Dropout and Academic Success" by Valentim Realinho, Jorge Machado, Luís Baptista, and Mónica V. Martins. It contains 4,424 records with 35 attributes, including demographic data, academic performance, and macroeconomic indicators. [Dataset Link](https://doi.org/10.5281/zenodo.5777340)

### Key Features:
- **Demographics:** marital status, nationality, displaced, gender, age at enrollment, and international
- **Socio-Economic:** parent qualification and occupation, educational special needs, debtor, tuition fees, and scholarship holder 
- **Macroeconomic:** unemployment rate, inflation rate, and GDP
- **Enrollment Date:** application mode, application order, course, attendance, and previous qualification
- **Academic Performance:** curricular units credited/enrolled/evaluated/approved/grade.
- **Target Variables:** student dropout or academic success.

### Dataset Columns

**File:** `dataset.csv`

| Column Name                                          | Description                                                                                           |
| ---------------------------------------------------- |-------------------------------------------------------------------------------------------------------|
| **Marital status**                                   | The marital status of the student. (Categorical)                                                      |
| **Application mode**                                 | The method of application used by the student. (Categorical)                                          |
| **Application order**                                | The order in which the student applied. (Numerical)                                                   |
| **Course**                                           | The course taken by the student. (Categorical)                                                        |
| **Daytime/evening attendance**                       | Whether the student attends classes during the day or in the evening. (Categorical)                   |
| **Previous qualification**                           | The qualification obtained by the student before enrolling in higher education. (Categorical)         |
| **Nacionality**                                      | The nationality of the student. (Categorical)                                                         |
| **Mother's qualification**                           | The qualification of the student's mother. (Categorical)                                              |
| **Father's qualification**                           | The qualification of the student's father. (Categorical)                                              |
| **Mother's occupation**                              | The occupation of the student's mother. (Categorical)                                                 |
| **Father's occupation**                              | The occupation of the student's father. (Categorical)                                                 |
| **Displaced**                                        | Whether the student is a displaced person. (Categorical)                                              |
| **Educational special needs**                        | Whether the student has any special educational needs. (Categorical)                                  |
| **Debtor**                                           | Whether the student is a debtor. (Categorical)                                                        |
| **Tuition fees up to date**                          | Whether the student's tuition fees are up to date. (Categorical)                                      |
| **Gender**                                           | The gender of the student. (Categorical)                                                              |
| **Scholarship holder**                               | Whether the student is a scholarship holder. (Categorical)                                            |
| **Age at enrollment**                                | The age of the student at the time of enrollment. (Numerical)                                         |
| **International**                                    | Whether the student is an international student. (Categorical)                                        |
| **Curricular units 1st sem (credited)**              | The number of curricular units credited by the student in the first semester. (Numerical)             |
| **Curricular units 1st sem (enrolled)**              | The number of curricular units enrolled by the student in the first semester. (Numerical)             |
| **Curricular units 1st sem (evaluations)**           | The number of curricular units evaluated by the student in the first semester. (Numerical)            |
| **Curricular units 1st sem (approved)**              | The number of curricular units approved by the student in the first semester. (Numerical)             |
| **Curricular units 1st sem (grade)**                 | The average grade of the curricular units credited in the first semester. (Numerical)                 |
| **Curricular units 1st sem (without evaluations)**   | The number of curricular units without evaluations in the first semester. (Numerical)                 |
| **Curricular units 2nd sem (credited)**              | The number of curricular units credited by the student in the second semester. (Numerical)            |
| **Curricular units 2nd sem (enrolled)**              | The number of curricular units enrolled by the student in the second semester. (Numerical)            |
| **Curricular units 2nd sem (evaluations)**           | The number of curricular units evaluated by the student in the second semester. (Numerical)           |
| **Curricular units 2nd sem (approved)**              | The number of curricular units approved by the student in the second semester. (Numerical)            |
| **Curricular units 2nd sem (grade)**                 | The average grade of the curricular units credited in the second semester. (Numerical)                |
| **Curricular units 2nd sem (without evaluations)**   | The number of curricular units without evaluations in the second semester. (Numerical)                |
| **Unemployment rate**                                | The unemployment rate in the student's area. (Numerical)                                              |
| **Inflation rate**                                   | The inflation rate in the student's area. (Numerical)                                                 |
| **GDP**                                             | The GDP in the student's area. (Numerical)                                                            |
| **Target**                                          | The target variable indicating whether the student graduated, enrolled, or dropped out. (Categorical) |

## Project Structure

```bash
data_exploration_student_success/
│
├── data/
│
├── notebooks/              
│   ├── 01_data_exploration.ipynb  # EDA and initial descriptive statistics.
│   ├── 02_preprocessing.ipynb     # Data cleaning and preprocessing.
│   └── 03_modeling.ipynb          # Modeling and predictions.
│
├── requirements.txt        # Dependencies required for the project.
├── README.md               # Project overview and instructions.
└── .gitignore              # Ignore unnecessary files in version control (e.g., .pyc files, datasets).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

