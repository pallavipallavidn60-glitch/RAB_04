# RAB_04 - Supervised Classification / Regression Modeling & Tuning

## Project Overview
This project focuses on building and evaluating multiple supervised machine learning models for customer churn prediction. The goal is to identify customers who are likely to leave a service by analyzing customer-related features and behavior.

## Objectives
- Load and explore the dataset.
- Perform data preprocessing and feature engineering.
- Split the dataset into training and testing sets.
- Train multiple baseline machine learning models.
- Compare model performance using evaluation metrics.
- Perform hyperparameter tuning to improve model accuracy.
- Select the best-performing model.

## Dataset
The project uses the Customer Churn dataset containing customer information such as:
- Demographic details
- Account information
- Service usage details
- Churn status (Target Variable)

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models
The following models were implemented and compared:

1. Logistic Regression
2. Random Forest Classifier
3. XGBoost / Gradient Boosting Classifier
4. Decision Tree Classifier

## Data Preprocessing
The following preprocessing techniques were applied:

- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test splitting
- Feature selection

## Hyperparameter Tuning
Grid Search Cross Validation was used to optimize model parameters and improve prediction performance.

## Evaluation Metrics
The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

## Results
The performance of all models was compared, and the best-performing model was selected based on evaluation metrics.

## Project Structure

RAB_04/
│
├── RAB_04_Modeling.ipynb
├── dataset.csv
├── README.md
└── outputs/

## Output
The project generates:
- Model training results
- Performance comparison
- Confusion matrix visualization
- Accuracy and evaluation reports

## Conclusion
This project demonstrates the complete workflow of supervised machine learning, including preprocessing, model training, evaluation, and hyperparameter tuning for customer churn prediction.
