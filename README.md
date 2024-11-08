# Machine Learning Techniques for Credit Card Fraud Detection

This project aims to implement several machine learning algorithms to detect credit card fraud. It employs a comprehensive, step-by-step approach, starting with data preprocessing, feature engineering, handling class imbalance, implementing several machine learning models, and evaluating them to identify the most effective model.

# Repository Contents
This repository contains the following file:
- `Credit_Card_Fraud_Detection.ipynb` - This Jupyter notebook encompasses all the steps and processes undertaken in this research project, including data preprocessing, feature engineering, model training, validation, and evaluation.

# Technologies Used
- Language: Python
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, imbalanced-learn, keras

# Steps

- Data Preprocessing and Understanding: Initial data handling, cleaning, and understanding.
- Feature Engineering: Extraction of new informative features from the existing variables.
- Handling Class Imbalance: Balanced the imbalanced dataset using SMOTE (Synthetic Minority Over-sampling Technique).
- Model Training: Models employed in the study include Gaussian Naive Bayes, Random Forest, K-Nearest Neighbors (KNN), XGBoost, and a simple Deep Neural Network.
- Model Validation and Evaluation: Evaluation was done using Receiver Operating Characteristic (ROC) curve and Area Under the ROC Curve (AUC) metrics.

# Running the Notebook
To run `Credit_Card_Fraud_Detection.ipynb`, follow these steps:

- Clone the repository
- Open Jupyter Notebook in your environment
- Navigate to the location of the cloned repository
- Open `Credit_Card_Fraud_Detection.ipynb`
- Run the notebook cells in order

# Data Source
The dataset for this project is obtained from Kaggle's "Credit Card Fraud Detection" challenge, which can be found [here](https://www.kaggle.com/mlg-ulb/creditcardfraud).

# Results
The project found XGBoost to be the most effective model in detecting credit card fraudulent transactions. For more detailed results, please refer to the Jupyter notebook.

# Contributions
Contributions, issues, and feature requests are welcome!

# Contact
If you have any questions, ideas, or concerns, please feel free to contact us. Happy coding!
