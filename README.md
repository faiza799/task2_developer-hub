# task2_developer-hub
# Credit Risk Prediction Project

 Objective
The objective of this project is to predict whether a loan applicant will default or get approved based on their personal and financial information using machine learning models.


 Dataset
Loan Prediction Dataset (loan_data_set.csv)

It includes the following features:
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target)



 Data Preprocessing
- Handled missing values:
  - Categorical → Mode
  - Numerical → Median
- Encoded categorical variables using LabelEncoder
- Removed Loan_ID (not useful for prediction)
- Applied feature scaling using StandardScaler



 Exploratory Data Analysis (EDA)
The following visualizations were performed:
- Loan Amount Distribution
- Applicant Income Distribution
- Education vs Loan Status

These visualizations helped in understanding data patterns and relationships.



  Machine Learning Models

Two classification models were used:

 1. Logistic Regression
- Used for binary classification
- Requires scaled data
- Evaluated using accuracy and confusion matrix

2. Decision Tree Classifier
- Captures non-linear patterns
- Works without assumptions on data distribution



 Model Evaluation

Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)



 Results
- Logistic Regression gives stable baseline performance
- Decision Tree captures complex patterns in data
- Credit History is a strong predictor of loan approval


 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn



 Conclusion
This project demonstrates a complete machine learning pipeline including data preprocessing, visualization, model training, and evaluation for credit risk prediction.
