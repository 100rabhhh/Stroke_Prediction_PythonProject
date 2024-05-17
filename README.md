# Stroke_Prediction_PythonProject

Stroke Prediction Analysis and Modeling Summary
Data Overview
The dataset includes information on individuals such as age, gender, marital status, work type, residence type, average glucose level, BMI, smoking status, and stroke occurrence. During preprocessing, rows with missing BMI values were dropped to ensure data quality.

Data Exploration
The dataset is imbalanced, with more individuals not having a stroke (0) compared to those who did (1). Exploratory analysis revealed higher stroke occurrences in older individuals, and those with hypertension and heart disease.

Data Preprocessing
To prepare the data for modeling, label encoding and one-hot encoding were applied to categorical variables. Rows with missing BMI values were removed to handle missing data.

Data Visualization
Countplots and histograms were utilized to visualize stroke occurrences across categorical and numerical features. Key variables like hypertension and heart disease were shown to significantly impact stroke occurrence.

Modeling
A logistic regression model was initially trained, which resulted in high accuracy but poor performance in predicting strokes (class 1) due to class imbalance. By applying SMOTE to oversample the minority class, the model's performance, particularly in terms of recall for stroke prediction, improved significantly.

Model Evaluation
The enhanced model achieved balanced performance with improved recall for stroke cases, indicating better identification of at-risk individuals. The confusion matrix and classification report provided detailed insights into model predictions.

Insights for Future Work
Further Exploration and Feature Engineering: To boost predictive power, further data exploration and feature engineering are recommended.
Model Enhancement: Testing additional models and performing hyperparameter tuning could improve model performance.
Continuous Monitoring: Regular updates and monitoring of the model with new data will enhance its effectiveness.
This project demonstrated my proficiency in data preprocessing, analysis, visualization, and model building using Python to predict stroke occurrences effectively.

#Python #DataAnalysis #StrokePrediction #MachineLearning #DataVisualization #Modeling #HealthcareAnalytics #DataScience #SMOTE #LogisticRegression






