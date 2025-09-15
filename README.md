🍷 Wine Quality Prediction
📌 Overview
This project applies machine learning classification models to predict the quality of red wine based on its physicochemical attributes. The dataset contains 1599 samples with 11 features (e.g., acidity, alcohol, sulphates) and a quality score ranging from 0 to 10.

📊 Dataset
Features:

Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Target Variable: quality (integer 0–10, grouped into "good" vs. "bad")

⚙ Data Preprocessing
Removed missing values (none found in dataset).

Standardized features using StandardScaler.

Converted wine quality into a binary classification problem:

1 → Good quality (≥ 7)
0 → Bad quality (< 7)
Stratified train-test split:

Training: 70%
Testing: 30%
🤖 Models Implemented
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
📈 Results
Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	0.87	0.85	0.81	0.83
Decision Tree	0.85	0.83	0.79	0.81
Random Forest	0.92	0.91	0.88	0.89
KNN (k=5)	0.88	0.86	0.83	0.84
SVM	0.89	0.87	0.85	0.86
📌 Best Model: Random Forest Classifier with 92% accuracy.

📊 Visualizations
Feature distributions
Correlation heatmap
Confusion matrices for all models
Feature importance from Random Forest

📬 Contact
✉ Email: nancnanbil647@gmail.com
🔗 LinkedIn: Nancy Nabil
