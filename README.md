Diabetes Prediction using Machine Learning

This project focuses on the early detection of diabetes by leveraging machine learning algorithms to automate the diagnostic process. By analyzing health-related features, the model aims to provide timely predictions that can help reduce the risk of long-term complications.

Dataset Description

The project utilizes the Pima Indians Diabetes Dataset sourced from Kaggle.


Total Records: 768 rows 


Features: 9 columns (8 input features and 1 output label) 


Key Indicators: Glucose, BMI, Age, Insulin, and Blood Pressure 


Data Cleaning: Inconsistencies like zero values in Glucose and BMI were treated as missing data and replaced with median values during the preprocessing stage.

Algorithms Implemented

The following models were developed and compared to find the most accurate diagnostic tool:


K-Nearest Neighbors (KNN): A "lazy learning" algorithm that classifies data based on the majority class of its closest neighbors.


Decision Tree: A structure that makes decisions by splitting data features at various nodes, similar to a flowchart.


Random Forest: An ensemble method that combines multiple decision trees to create a more robust and accurate classifier.

Results and Evaluation

The models were evaluated based on Accuracy, Precision, Recall, F1 Score, and Root Mean Square Error (RMSE).

Model         Accuracy  Precision  Recall  F1 Score  RMSE

Random Forest 0.84        0.82      0.86    0.84      0.39

Decision Tree 0.80        0.78      0.81    0.79      0.46

KNN           0.78        0.76      0.80    0.78      0.45


Final Conclusion

The Random Forest model is the most effective for this prediction task. It achieved the highest accuracy (84%) and the lowest error rate (RMSE 0.39). Its success is attributed to its ensemble learning approach, which handles complex data effectively and avoids the overfitting issues often found in individual decision trees.
