# Credit-Card-Approval
This project aims to predict whether a credit card application will be approved or rejected based on applicant information. Using a cleaned dataset containing demographic, financial, and employment details, various classification machine learning models are applied and compared to identify the most accurate and reliable approach.

**Objectives**

Build predictive models to classify credit card applications as approved or rejected.

Perform data preprocessing and feature engineering to prepare the dataset.

Evaluate multiple classification algorithms and select the best-performing model.

Interpret model outputs to understand key factors influencing approval decisions.

**Dataset Description**

The dataset includes the following features:

Demographics: Gender, Age, Ethnicity, Citizenship

Financials: Debt, Income, Credit Score, Prior Default

Employment: Years Employed, Industry, Employment Status

Other: Marital Status, Bank Customer Status, Driver’s License, Zip Code

Target Variable: Approved (1 = Approved, 0 = Rejected)

**Tools & Technologies**

Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Models: Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, K-Nearest Neighbors, GaussianNB

Metrics: Accuracy, Precision, Recall, F1-Score

**Key Insights**

Features like Credit Score, Income, Years Employed, and Prior Default significantly influence approval outcomes.

Support Vector Machine and Random Forest showed strong performance in terms of accuracy and recall.

Proper feature scaling and encoding were critical for model success.

**Future Enhancements**

Integrate explainability tools like SHAP or LIME for model transparency.

Deploy the model as a web-based application for real-time predictions.

Expand dataset with additional features like spending behavior or credit history.
