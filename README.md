# ACE6313 - Student Academic Performance Prediction

SDG 4: Quality Education — Using machine learning to identify at-risk students and support better educational outcomes.

## Project Overview
This project applies machine learning to predict students' academic performance based on background, lifestyle, and social habit factors. Early identification of at-risk students can help educators intervene sooner and improve learning outcomes — directly supporting UN SDG 4: Quality Education

## 📊 Dataset
Name: Students Academic Performance Dataset \
Source: Kaggle — itszubi/students-academic-performance-dataset \
Size: 6,600 rows × 20 columns \
Features: Student background, lifestyle, and social habits \
Target: Academic performance (grade/category)

## Summary of Results
|Model|R2|RMSE|MAE|
|---|---|---|---|
|Linear Regression|0.7467 |1.8922|0.6664|
|Decision Tree|0.5572|2.5019|1.4894|
|Random Forest|0.6839|2.1139|1.0050|
|SVR|0.7477|1.8883|0.6407|
|kNN|0.6473|2.2329|1.1979|

Best model: SVR (R2 = 0.7477)
