Stroke Prediction Model Evaluation

In this project, k-Nearest Neighbors (kNN) and Logistic Regression models were compared for stroke prediction. The goal is to predict whether a patient is likely to have a stroke based on demographic and health-related data.

Dataset

Dataset Path: Data/stroke.csv

Features:

id: Unique identifier (not considered for modeling)

gender: Gender (categorical)

age: Age (numerical)

hypertension: Hypertension status (0 = No, 1 = Yes)

heart_disease: Heart disease status (0 = No, 1 = Yes)

ever_married: Marital status (categorical)

work_type: Type of work (categorical)

Residence_type: Rural or Urban (categorical)

avg_glucose_level: Average glucose level (numerical)

bmi: Body mass index (numerical)

smoking_status: Smoking status (categorical)

stroke: Target variable (1 = Stroke, 0 = No Stroke)

Model Evaluation

3.2 Precision-Recall Curves

Logistic Regression: Initially, it provides high precision, but performance drops as recall increases. The curve fluctuates quickly.
kNN: The curve is more balanced, but it generally shows lower performance.
3.3 Model Comparison

Evaluation Metrics:
Logistic Regression generally performs more consistently and successfully predicts positive classes.
kNN struggles to distinguish positive classes and shows lower performance overall.

Results:
Logistic Regression: It is more suitable and consistent due to the linear separability of the data.
kNN: The model struggles to distinguish positive classes due to class imbalance.

Conclusion:
Logistic Regression is a more suitable and powerful model for this dataset. kNN faces challenges due to class imbalance.
