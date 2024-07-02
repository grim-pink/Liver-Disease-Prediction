# Liver Disease Prediction ML Project
Project Overview
This project aims to predict liver disease using machine learning techniques. By leveraging various models and data preprocessing methods, the team sought to improve the accuracy and reliability of predictions.

Dataset
The dataset used for this project was sourced from Kaggle. It contains 30691 records with 11 features, including patient demographics and medical test results.

Data Preprocessing
Missing Value Handling: Missing values were imputed using Median Imputation.
Encoding Categorical Features: Used the category_encoders library for encoding categorical features.
Normalization: Numerical features were normalized using MinMaxScaler.

Models Used
Naive Bayes
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Evaluation Metrics
The models were evaluated based on the following metrics:

Accuracy
Precision
F1 Score
ROC-AUC Curve
Confusion Matrix

Results
Random Forest: Achieved the highest accuracy of 99.43%.
Other models showed varying degrees of performance, but none surpassed the Random Forest model.
Conclusion
The machine learning project for liver disease prediction showcased notable success, with the Random Forest model achieving the highest accuracy of 99.43%. This approach not only offers substantial savings in diagnostic costs but also marks a significant advancement in early detection. The project's findings affirm the potential of machine learning in enhancing healthcare outcomes, especially in settings with limited resources, and set a promising direction for future research in predictive medicine.

Future Work
For future work, further validation on different datasets is required to evaluate the model’s performance on unseen data.
