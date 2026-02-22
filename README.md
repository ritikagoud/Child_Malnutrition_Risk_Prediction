#  AI-Based Early Detection of Child Malnutrition

##  Overview

Child malnutrition remains a serious public health concern, especially in developing regions. Early detection of moderate and severe malnutrition is essential to prevent long-term health complications.

This project implements a Machine Learning-based classification system that predicts the nutritional status of children using anthropometric health indicators.

---

##  Problem Statement

Traditional screening methods rely heavily on manual assessment and may not always provide early predictive insights.  

The objective of this project is to develop a data-driven system that analyzes measurable health parameters and accurately classifies children into:

- **Normal**
- **Moderate Malnutrition**
- **Severe Malnutrition**

---

##  Dataset Description

The dataset contains **5000 individual child health records** with the following features:

- `age_months`
- `weight_kg`
- `height_cm`
- `muac_cm`
- `bmi`
- `nutrition_status` (Target Variable)

The target variable includes three classes:

- Normal  
- Moderate  
- Severe  

---

##  Methodology

The following steps were performed:

1. Data loading and validation  
2. Label encoding of the target variable  
3. Stratified train-test split (80% training, 20% testing)  
4. Model training using **Random Forest Classifier**  
5. Performance evaluation using:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
6. Feature Importance analysis  

---

##  Model Performance

- **Accuracy:** 94.7%

The confusion matrix demonstrates strong classification performance across all three categories.

Feature importance analysis identified **Mid Upper Arm Circumference (MUAC)** as the most influential predictor of malnutrition risk.

---

##  Technologies Used

- Python  
- Jupyter Notebook  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

---

##  Conclusion

The developed model successfully classifies children into nutritional categories with high accuracy.  

This approach demonstrates how Machine Learning can support healthcare professionals in early screening and risk prioritization, enabling timely intervention strategies.
