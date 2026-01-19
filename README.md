This project focuses on predicting the likelihood of a disease in a patient using structured medical data.
The goal is not just to build a model, but to follow industry-reliable machine learning practices that are commonly used in healthcare and medical risk-prediction systems.

The project simulates a real-world medical scenario, where patient records contain noise, missing values, class imbalance, and medically meaningful features such as cholesterol, blood pressure, heart rate, and blood sugar levels.




Approach & Methodology

The project follows an end-to-end machine learning workflow, similar to what is used in professional healthcare ML pipelines.

1️⃣ Data Understanding & Inspection

Reviewed feature meanings from a medical perspective

Identified numerical, binary, and categorical variables

Checked class distribution of the target variable

2️⃣ Data Cleaning & Preprocessing

Handled missing values using statistically appropriate methods

Ensured no data leakage between training and test sets

Applied feature scaling where required (distance-based models)

3️⃣ Handling Class Imbalance

Since disease datasets are naturally imbalanced:

Used SMOTE and class weighting techniques

Focused on improving recall for the diseased class

This step reflects real healthcare ML practices, where recall is often prioritized over raw accuracy.

4️⃣ Model Development

Trained and compared multiple classification models:

Logistic Regression

Support Vector Machine (SVM)

Random Forest

Each model was evaluated using medically relevant metrics rather than accuracy alone.

5️⃣ Model Evaluation

Used:

Confusion Matrix

Precision

Recall

F1-Score

Evaluation focused on clinical reliability, especially the model’s ability to correctly identify patients with disease.

in healthcare:

False Negatives (missing a disease) are more dangerous than false positives

Therefore, Recall and F1-Score are emphasized

Accuracy is treated as a secondary metric