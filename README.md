# Credit-card-fraud-detection
## Overview
This project aims to detect fraudulent transactions in credit card data using machine learning algorithms. It involves preprocessing the data, training various classification models, and evaluating their performance.

## Dataset
The dataset used in this project contains credit card transactions labeled as fraudulent or legitimate. It consists of features such as transaction amount, time, and anonymized numerical features obtained from PCA.

## Installation
To run the code in this project, follow these steps:

Clone this repository to your local machine.
Install the required dependencies listed in the requirements.txt file using pip:
Copy code
pip install -r requirements.txt
Usage
*Preprocessing:* Run the preprocess_data.py script to preprocess the dataset. This script handles tasks such as handling missing values, scaling features, and splitting the data into training and testing sets.

*Training:* Train the machine learning models using the train_models.py script. This script trains multiple classification models, including logistic regression, random forest, and XGBoost, and saves the best-performing model.

*Evaluation:* Evaluate the performance of the trained models using the evaluate_models.py script. This script calculates metrics such as accuracy, precision, recall, and F1-score for each model on the test dataset.

*Deployment:* Deploy the best-performing model for inference using the deploy_model.py script. This script loads the saved model and makes predictions on new data.
