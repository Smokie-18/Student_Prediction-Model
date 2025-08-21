# Student_Prediction-Model
The goal of this notebook is to predict students’ exam scores based on study habits and lifestyle factors (e.g., hours studied, social media usage, attendance, etc.) using Linear Regression and Multiple Linear Regression.
📊 Dataset

The dataset (student_performance_regression.csv) contains the following key features:

hours_studied → Time spent studying.

sleep_hours → Average daily sleep.

attendance_pct → Class attendance percentage.

prev_gpa → Previous GPA.

practice_tests → Practice test performance.

tutorials_watched → Extra study material consumed.

social_media_hrs → Time spent on social media.

exam_score → 🎯 Target variable (final exam score).


1. Simple Linear Regression (One Feature)

First model: hours_studied → exam_score.
Trained model & extracted slope (coefficient) and intercept.
Visualized with scatter plot + regression line.
Second model: social_media_hrs → exam_score
Again trained model, extracted slope & intercept.
Visualized with scatter plot + regression line.

Interpretation:
More hours studied → higher predicted score.
More hours on social media → lower predicted score.


2. Multiple Linear Regression (Two Features)

Used both hours_studied & social_media_hrs to predict exam_score.
Performed train-test split (80/20).
Fitted model and generated predictions for both training and testing data.
Extracted model parameters:
Intercept (offset)
Coefficients (slopes for each feature)

3.📊 Model Evaluation(Regression Metrices)

Metrics were calculated for both training and testing sets:
MAE (Mean Absolute Error) → average error in predictions.
RMSE (Root Mean Squared Error) → typical error size in exam score units.
R² Score → proportion of variance explained by the model.




