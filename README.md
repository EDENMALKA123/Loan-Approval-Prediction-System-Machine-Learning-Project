# Loan Approval Prediction System – Machine Learning Project

This project presents a data-driven approach to predicting loan approval outcomes using real-world financial data.  
The goal was to help financial institutions identify which applicants are likely to repay their loans and which may default,  
by combining statistical reasoning with modern machine learning methods.

I worked with a dataset of 1,000 loan applications containing 14 features, including loan amount, annual income, interest rate, employment length, and home ownership.  
The outcome variable, *loan_status*, was recoded into a binary form: 0 for fully repaid loans and 1 for defaulted loans.

After cleaning the data and handling missing values, I explored the relationships between financial indicators such as interest rate, debt-to-income ratio (DTI), and income levels.  
The analysis revealed clear trends — higher interest rates and higher DTI were both linked to greater default risk, while home ownership appeared to slightly reduce risk.

For the modeling phase, I compared several machine learning algorithms, including Logistic Regression, Random Forest, Gradient Boosting, k-Nearest Neighbors (kNN), Naive Bayes, and a simple Neural Network (MLP).  
Each model was evaluated using 10-fold stratified cross-validation to ensure reliable and unbiased performance estimates.

Among them, **Logistic Regression** offered the best balance between accuracy and explainability —  
achieving an AUC of 0.931 and an overall accuracy of 0.889, while maintaining high recall (0.949) and precision (0.917).  
This means the model not only predicts accurately but also provides interpretable insights that can be trusted by loan officers and regulators.

The final outcome is a transparent and effective **Loan Recommendation System** capable of helping banks make better, data-driven credit decisions.
