### README for "Sure Tomorrow" Insurance Company Project

## Project Description

The insurance company "Sure Tomorrow" aims to address several issues using machine learning. The tasks include:

1. **Client Similarity:** Identifying clients similar to a specific client criteria to facilitate marketing strategies.
2. **Insurance Claim Prediction:** Predicting whether a new client is likely to make an insurance claim and comparing the prediction accuracy against a dummy model.
3. **Claim Amount Prediction:** Using linear regression to predict the amount of insurance claims a new client might make.
4. **Data Privacy Protection:** Developing a data transformation algorithm to protect clients' personal information without compromising the model's accuracy.

The project emphasizes the importance of data obfuscation techniques to prevent misuse of personal information if the data falls into the wrong hands. The goal is to prove the accuracy of the obfuscation algorithm rather than selecting the best model.

## Project Instructions

### 1. Load the Data
- Ensure the data is free from issues such as missing values and outliers.
- The dataset is located at `/datasets/insurance_us.csv`.

### 2. Task Execution
- **Task 1:** Find clients similar to a given client criteria to aid marketing efforts.
- **Task 2:** Predict if a new client is likely to make an insurance claim and compare the model’s performance to a dummy model.
- **Task 3:** Predict the amount of insurance claims a new client might make using a linear regression model.
- **Task 4:** Protect clients' personal data while maintaining the accuracy of the machine learning models.

### 3. Data Analysis and Preparation
- Verify data integrity and cleanliness.
- Ensure no missing values or outliers are present.
- Preprocess the data as required for each task.

### 4. Model Development
- Implement models for each task.
- Evaluate models using appropriate metrics.
- Ensure the data obfuscation technique maintains the model’s accuracy.

### 5. Conclusion
- Summarize findings and results for each task.
- Discuss the effectiveness of the data obfuscation algorithm.

## Data Description

The dataset includes the following features:
- **gender**: Gender of the insured person.
- **age**: Age of the insured person.
- **salary**: Salary of the insured person.
- **family_members**: Number of family members of the insured person.
- **claim_amount**: The amount of insurance claims made by the insured person over the last five years.

## Steps Taken

1. **Data Preparation:**
   - Loaded and examined the data files.
   - Ensured data cleanliness and addressed any missing values or outliers.

2. **Task Execution:**
   - Implemented models to identify similar clients.
   - Predicted insurance claims and compared model performance to a dummy model.
   - Predicted claim amounts using linear regression.
   - Developed and evaluated a data obfuscation algorithm to protect client information.

3. **Analysis and Evaluation:**
   - Analyzed changes in client data.
   - Compared model performance before and after data obfuscation.
   - Ensured model accuracy and effectiveness.

## Conclusion

This project involves preparing and analyzing insurance data to develop predictive models for client similarity, insurance claim likelihood, and claim amounts. It also includes implementing data obfuscation techniques to protect client information without compromising model accuracy. The results aim to enhance marketing strategies, improve claim prediction accuracy, and ensure data privacy.
