# Random Forest Classification – Customer Churn Prediction

## Project Overview
This project uses a **Random Forest Classification Algorithm** to predict whether a telecommunications customer will leave the company (Churn) or continue using its services.

## Dataset
- **Dataset Name:** Telco Customer Churn
- **Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Total Records:** 7,043
- **Target Variable:** Churn (Yes/No)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Project Workflow
1. Import required libraries.
2. Load and explore the dataset.
3. Handle missing values.
4. Encode categorical variables.
5. Separate features (X) and target (y).
6. Split the dataset into training and testing sets.
7. Build and train the Random Forest Classifier.
8. Predict customer churn.
9. Evaluate model performance.
10. Visualize the confusion matrix and feature importance.
11. Perform hyperparameter tuning and cross-validation.
12. Save the trained model using Joblib.

## Model Evaluation
The original Random Forest model achieved:

- **Accuracy:** 78.64%
- **Precision:** 62.37%
- **Recall:** 49.20%
- **F1-Score:** 55.01%

## Key Findings
The model identifies customers who are likely to leave the telecommunications company. Feature importance helps understand which customer characteristics influence churn prediction.

## Conclusion
This project demonstrates how machine learning and Random Forest Classification can help telecommunications companies predict customer churn and improve customer retention strategies.

## Project Files
- `Random_Forest_Project.ipynb` – Complete source code.
- `Random_Forest_Classification_Report.pdf` – Project summary report.
- `random_forest_model.pkl` – Saved trained model (if included).

---
**Project Type:** AI/ML – Classification  
**Algorithm:** Random Forest Classifier
