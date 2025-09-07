Loan Status Prediction Project | Machine Learning
Overview
This project is a machine learning-based solution to a financial risk assessment problem. The primary goal is to predict the approval status of a loan application.
By developing and evaluating multiple classification models, this project demonstrates a complete data science workflow, from data preprocessing to model evaluation. 
The final model is a powerful tool for a financial institution to streamline its loan approval process, make data-driven decisions, and mitigate risk.

Data and Methodology
The project uses a dataset containing various features of loan applicants, such as credit history, income, education, and marital status. The methodology is structured around a clear machine learning pipeline:

Exploratory Data Analysis (EDA) & Preprocessing: The initial data is cleaned to handle missing values and prepare categorical features for modeling. 
This step involves using libraries like Pandas for data manipulation and Seaborn for visualization to understand the underlying patterns and relationships within the dataset.

Feature Engineering: Features are created and transformed to improve model performance. This includes one-hot encoding for categorical variables and feature scaling where necessary.

Model Development: Two different classification algorithms were implemented to address the problem:

Support Vector Machine (SVM): A model that finds the optimal hyperplane to separate the loan approval classes.

Random Forest Classifier: An ensemble learning method that builds multiple decision trees and combines their predictions to produce a more accurate result.

Model Evaluation: The performance of both models was rigorously evaluated on an unseen test set. The models were assessed using key metrics such as accuracy, precision, recall, and the F1-score. A classification report and confusion matrix were generated to provide a comprehensive view of the model's performance on each class (approved vs. rejected).

Key Results
The Random Forest Classifier proved to be the superior model, demonstrating excellent performance and robustness.
Final Test Accuracy: 83.3%
Test ROC AUC: 80.2%

These results confirm the model's strong ability to generalize and correctly predict loan approval status.

Technologies Used
Python: The core programming language for the project.

Pandas & NumPy: For data manipulation and numerical operations.

Scikit-learn: The primary library for machine learning, including model building, evaluation, and data preprocessing.

Seaborn & Matplotlib: Used for creating informative visualizations to support the analysis.
