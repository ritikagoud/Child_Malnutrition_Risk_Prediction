AI Based Early Detection of Child Malnutrition
Overview

Child malnutrition remains a critical public health challenge, especially in developing regions. Early identification of moderate and severe malnutrition can significantly reduce long term health risks and improve intervention outcomes.

This project presents a machine learning based classification system that predicts the nutritional status of children using anthropometric health indicators.

Problem Statement

Manual screening methods may not always provide predictive insight into malnutrition risk. There is a need for a data driven system that can analyze measurable health parameters and accurately classify children into nutritional risk categories.

Dataset Description

The dataset consists of 5000 individual child health records with the following features:

Age in months

Weight in kilograms

Height in centimeters

Mid Upper Arm Circumference

Body Mass Index

Nutrition status label

The target variable includes three classes:

Normal

Moderate

Severe

Methodology

The following steps were performed:

Data loading and validation

Label encoding of the target variable

Stratified train test split

Model training using Random Forest Classifier

Performance evaluation using accuracy, classification report, and confusion matrix

Feature importance analysis

Model Performance

The Random Forest model achieved an accuracy of 94.7 percent on the test dataset.

The confusion matrix indicates strong classification capability across all three nutritional categories. Feature importance analysis shows that Mid Upper Arm Circumference is the most significant predictor of malnutrition risk, which aligns with medical understanding.

Tools and Technologies

Python

Jupyter Notebook

pandas

matplotlib

seaborn

scikit learn

Conclusion

The developed model demonstrates that machine learning can effectively assist in early detection of child malnutrition. Such systems can support healthcare workers in prioritizing high risk cases and improving intervention strategies.
