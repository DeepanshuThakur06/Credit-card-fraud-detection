# Credit Card Fraud Detection Project
**Project Overview**
![image](https://github.com/user-attachments/assets/750f01de-46d2-4324-be06-ac9875e4459e)

The Credit Card Fraud Detection project focuses on developing a robust machine learning model to identify fraudulent transactions. This project includes data preprocessing, exploratory data analysis, feature engineering, model selection, hyperparameter tuning, and performance evaluation.

**Key Features**

* **Data Preprocessing:** Cleaned and explored the dataset to handle class imbalance and prepare it for modeling.
* **Feature Engineering:** Applied techniques to extract meaningful features and used outlier detection methods (IQR and Box-Cox transformation) to enhance model performance.
* **Model Selection:** Evaluated and compared multiple algorithms including Logistic Regression, Random Forest, and XGBoost.
* **Hyperparameter Tuning:** Optimized model performance using GridSearchCV and RandomizedSearchCV.
* **Performance Evaluation:** Assessed models using metrics like Precision, Accuracy, F1-score, and ROC-AUC.

**Best Model**

* Model: XGBoost (Optimized)
* Training Precision: 0.954955
* Testing Precision: 0.925373
* Training Accuracy: 0.999648
* Testing Accuracy: 0.999418
* Training F1-score: 0.888268
* Testing F1-score: 0.789809
XGBoost (Optimized) showed the best balance of precision and performance across training and testing datasets, making it the most effective model for this project.

**Future Work**
Regularly update and re-evaluate models to adapt to evolving fraud patterns.
Explore additional feature engineering and advanced algorithms for further improvement.
