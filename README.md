# Email-Campaign-Prediction
## Overview
This project aims to predict the effectiveness of email marketing campaigns using machine learning models. By analyzing customer behavior and engagement data, the model classifies campaign outcomes, helping businesses improve their marketing strategies.

## Key Features
Data Analysis: Exploratory Data Analysis (EDA) to uncover patterns and relationships in the data.
Modeling: Various classification models (Logistic Regression, Random Forest, SVM, etc.) are used to predict campaign success.
Evaluation: Models are evaluated using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.
## Dataset
The dataset includes:
- Demographics: Age, gender, location, etc.
- Engagement: Email clicks, opens, and website interactions.
- Campaign Info: Campaign ID, email type, send time, etc.

## How to Run
- Clone the repository:
git clone https://github.com/dhananjayt23/email-campaign-effectiveness-prediction.git
cd email-campaign-effectiveness-prediction
- Install dependencies:
pip install -r requirements.txt
- Run the notebook:
jupyter notebook

## Models and Techniques
Models: Logistic Regression, Random Forest, SVM, Gradient Boosting.
Preprocessing: One-hot encoding, standardization, and class balancing using SMOTE.
Evaluation: Confusion Matrix, ROC Curve, and AUC-ROC.
Results
The Random Forest Classifier achieved the best results with an accuracy of XX% and an AUC-ROC score of XX. It successfully predicted the likelihood of campaign success based on customer data.

## Technologies Used
Python, Pandas, Matplotlib, Scikit-learn for modeling and visualization.
Jupyter Notebook for development and analysis.
Future Improvements
Hyperparameter Tuning for better model performance.
Deployment of the model for real-time use by marketing teams.
