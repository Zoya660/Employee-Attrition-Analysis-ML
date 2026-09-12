# Employee Attrition Analysis Using Machine Learning

## Project Overview

Employee attrition is a major challenge for organizations because losing employees can increase recruitment and training costs.

This project uses Machine Learning to analyze employee data and predict whether an employee is likely to leave the company.

## Objective

The main objective is to build a machine learning model that can identify employees who may be at risk of attrition based on factors such as:

- Job satisfaction
- Overtime
- Monthly income
- Job role
- Age
- Years at company
- Total working years
- Other employee-related factors

## Dataset

Dataset: IBM HR Analytics Employee Attrition & Performance

The dataset contains employee information and an `Attrition` target variable.

- Total records: 1470
- Total features: 34
- Target variable: Attrition

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Machine Learning Models

Two classification algorithms were implemented:

1. Logistic Regression
2. Random Forest Classifier

### Model Performance

| Model | Accuracy | Recall | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 86.05% | 34.04% | 81.07% |
| Random Forest | 84.69% | 14.89% | 81.21% |

Logistic Regression was selected as the better overall model because it achieved higher accuracy and significantly higher recall.

## Project Workflow

1. Data loading
2. Data exploration
3. Missing-value checking
4. Duplicate-value checking
5. Exploratory Data Analysis
6. Data preprocessing
7. Train-test split
8. Logistic Regression
9. Random Forest
10. Model evaluation
11. Confusion matrix
12. ROC curve
13. Feature importance analysis

## Key Visualizations

The project includes analysis of:

- Employee attrition distribution
- Attrition by overtime
- Attrition by job role
- Attrition by job satisfaction
- Monthly income vs attrition
- Confusion matrix
- ROC curve

## Conclusion

The project demonstrates how machine learning can be applied to employee attrition analysis.

Logistic Regression achieved an accuracy of 86.05% and a ROC-AUC score of 81.07%, making it the better overall model for this dataset.

The analysis can help organizations identify potential employee attrition patterns and support data-driven employee retention strategies.

## Future Improvements

- Hyperparameter tuning
- Class imbalance handling
- Feature selection
- Threshold optimization
- Testing additional machine learning algorithms
- Deployment as a web application

## Author

**Zoya**
