# AAI-510-project-Lifestyle-Based-Diabetes-Prediction-Personalized-Recommendation-System
AAI-510 project Lifestyle Based Diabetes Prediction Personalized Recommendation System
Lifestyle-Based Diabetes Prediction & Personalized Recommendation System
Project Overview
This project leverages machine learning and deep learning models to predict the likelihood of diabetes in individuals based on lifestyle and health-related attributes. It also provides basic personalized recommendations and uses LIME (Local Interpretable Model-Agnostic Explanations) to make predictions transparent and interpretable.

Key Features
Data Preprocessing:

Handled class imbalance using SMOTE + Tomek Links.

Standardized features for consistent model input.

Modeling Techniques:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors

XGBoost

Neural Network (with regularization and advanced architecture)
Evaluation Metrics:

Accuracy, Precision, Recall, F1-score

Confusion Matrix

Model comparison for performance insights

Explainability:

Integrated LIME to explain individual predictions and feature contributions.

🖥Interactive Form Interface:

Developed using ipywidgets for real-time diabetes prediction based on user input.

Provides prediction along with LIME-based explanation and risk categorization.

How to Run
Install Required Packages:

bash
Copy
Edit
pip install -r requirements.txt
(Or individually install)

bash
Copy
Edit
pip install pandas numpy scikit-learn xgboost tensorflow lime imbalanced-learn ipywidgets matplotlib seaborn
Launch the Notebook:
Open the notebook Copy_of_Trial (4).ipynb in Jupyter Notebook or Google Colab.

Use the Form Interface:
Scroll to the section with widgets to input lifestyle attributes.
Click the “Predict Diabetes” button to see the predicted class and explanation.

