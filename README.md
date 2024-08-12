# Bug Severity Prediction

This project aims to predict the severity of software bugs using advanced machine learning techniques. The primary challenge encountered was class imbalance in the dataset. To address this, we employed boosting and ensemble learning methods, specifically XGBoost and Random Forest, to develop optimized models. The project highlights the use of various strategies to mitigate data imbalance without resorting to oversampling or undersampling, ensuring a balanced and effective model performance.

## Project Overview

The objective of this project is to accurately predict the severity levels of software bugs. The project encompasses several key steps, including data preprocessing, feature engineering, model selection, and performance evaluation. By leveraging the strengths of ensemble methods, we aimed to build robust models capable of handling imbalanced data.

## Techniques and Methods

### 1. Data Preprocessing
- **Data Cleaning**: Removal of duplicates, handling missing values, and normalization of data.
- **Feature Engineering**: Creation of new features from existing data to enhance model performance.
- **Class Imbalance Handling**: Implementation of techniques to manage class imbalance without data augmentation.

### 2. Machine Learning Techniques
- **XGBoost (Extreme Gradient Boosting)**: 
  - Utilized for its efficiency and accuracy in handling large datasets and complex relationships.
  - Hyperparameter tuning was performed to optimize the model's performance.
  - Managed class imbalance using the `scale_pos_weight` parameter.

- **Random Forest**:
  - Applied as an ensemble learning method, combining multiple decision trees to improve predictive accuracy.
  - Addressed class imbalance using class weighting and focused on feature importance to enhance model interpretability.

### 3. Model Evaluation
- **Performance Metrics**:
  - **Accuracy**: Overall accuracy of the model in predicting the correct severity levels.
  - **Precision, Recall, and F1-Score**: Evaluated for each class to understand the model's performance in distinguishing between different severity levels.
  - **Confusion Matrix**: Visualized to assess the model's performance across all classes.
  - **ROC-AUC and Precision-Recall AUC**: Used to measure the model's ability to distinguish between classes, particularly useful in imbalanced datasets.

## Contributors

This project was developed and completed by the following contributors:

- **İpek Uzun** - (https://github.com/ipek-uzun)
- **Selman Yılmaz** - (https://github.com/mesely)
