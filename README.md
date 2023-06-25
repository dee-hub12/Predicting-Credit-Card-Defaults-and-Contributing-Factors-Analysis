# Loan Default Prediction and Contributing Factors Analysis

**Description:**
This project predicts credit card defaults and identifies the key factors contributing to default payments. By leveraging a dataset containing information on credit card clients, demographic factors, credit data, and payment history, we aim to develop a robust machine learning model that can accurately predict whether a client will likely default on their payment next month.

Through extensive exploratory data analysis (EDA), we investigate the relationships between variables such as credit amount, gender, education, marital status, age, repayment status, bill statements, and payment amounts. We perform statistical tests, including chi-square and Mann-Whitney, to determine the significant associations and differences between defaulters and non-defaulters.

To improve model performance, we employ feature engineering techniques by aggregating payment details for each month and preprocessing the data using encoding and scaling. Four different machine learning algorithms, including Logistic Regression, Random Forest, XGBoost, and SVM, are trained and evaluated on their ability to predict loan defaults. The evaluation metrics, such as the F1 score and ROC AUC score, are used to assess model performance, considering the imbalanced nature of the dataset.

Based on the findings, XGBoost emerges as the best-performing model, demonstrating a slightly higher F1 score and ROC AUC score compared to other algorithms. The payment delay variables, particularly the delay of 2 months in the previous month (PAY_1), are identified as crucial factors in predicting default payments.

The project concludes with recommendations to address the challenges of predicting loan defaults, such as implementing balanced sampling techniques to address the class imbalance, further exploring feature engineering opportunities, and investigating additional external data sources to enhance the model's predictive capabilities.

