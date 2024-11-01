# Customer Churn Analysis and Segmentation for Subscription-Based Services

This project focuses on reducing customer churn for subscription-based businesses by predicting potential churners and segmenting customers based on usage patterns and demographics. By understanding and addressing customer behaviors, this analysis helps improve retention and overall business performance.

## Project Overview
The project analyzes customer data to identify key risk factors associated with churn. It applies several machine learning models to predict churn and segments customers into groups for targeted retention strategies.

### Key Features
- **Churn Prediction**: Predicts customer churn using metrics such as monthly revenue, usage frequency, and contract details.
- **Customer Segmentation**: Groups customers based on behavior, enabling personalized retention efforts.
- **Model Comparison**: Evaluates models like Random Forest, Logistic Regression, XGBoost, and SVC based on metrics including precision, recall, F1 score, and AUPRC (Area Under the Precision-Recall Curve).

### Models and Evaluation
- **Logistic Regression**:
  - AUPRC: 0.932, F1 Score: 0.852
- **Random Forest**:
  - AUPRC: 0.955, F1 Score: 0.883
- **SVC**:
  - AUPRC: 0.947, F1 Score: 0.867
- **XGBoost**:
  - AUPRC: 0.957, F1 Score: 0.889

### Business Implications
High-performing models allow for precise churn prediction, identifying customers likely to leave. Customer segmentation facilitates personalized retention strategies, enhancing satisfaction and loyalty and supporting revenue growth.

## Project Structure
- **Data Preprocessing**: Data cleaning, handling of missing values, and encoding of categorical variables.
- **Exploratory Data Analysis**: Analysis of customer demographics, usage patterns, and churn behavior.
- **Modeling**: Model training and evaluation, using SMOTE to manage class imbalance and improve accuracy.
- **Segmentation**: Customer clustering for targeted retention strategies.
