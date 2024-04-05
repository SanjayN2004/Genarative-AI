# Generative AI

Liver Disease Prediction using Keras
This repository contains code for building a binary classification model using Keras to predict liver disease.

Requirements
Python 3.x
Jupyter Notebook (optional)
Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, keras
You can install the required libraries using pip:

bash
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn keras
Dataset
The dataset used for training the model is located in the file indian_liver_patient.csv. This dataset contains various attributes related to liver health, such as age, gender, total proteins, albumin, etc.

Code
The main code is provided in the file liver_disease_prediction.py. It performs the following steps:

Data preprocessing: Reading the dataset, handling missing values, converting categorical variables to numerical using one-hot encoding, and splitting the data into features and target variable.
Train-test split: Splitting the data into training and testing sets.
Feature scaling: Standardizing the features to have a mean of 0 and a standard deviation of 1.
Model building: Creating a sequential model using Keras with multiple dense layers and dropout regularization.
Model training: Compiling and training the model using the training data.
Model evaluation: Making predictions on the test data and evaluating the model performance using confusion matrix, classification report, and accuracy score.
How to Use
Clone this repository:
bash
Copy code
git clone https://github.com/your_username/liver-disease-prediction.git
cd liver-disease-prediction
Ensure you have the dataset indian_liver_patient.csv in the same .
