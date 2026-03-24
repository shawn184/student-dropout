# Project Title

This project addresses the prediction of student dropout rates using machine learning models. The primary objective is to identify students at risk of dropping out based on various input features. Below is a detailed description of the project components:

## 1. Preprocessing and Grouping Steps
- **Data Cleaning**: Null values and inconsistencies were addressed through imputation and normalization techniques. 
- **Feature Engineering**: Important features were derived from raw data to improve model performance. Features included demographic information, academic history, and engagement metrics. 
- **Grouping**: Data was segmented into different groups based on key characteristics such as age, program of study, and previous academic performance to enhance predictive accuracy.

## 2. Modeling Approach
1. **Model Selection**: Various models were tested, including Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines. Each model's performance was evaluated using cross-validation techniques for robustness.
2. **Hyperparameter Tuning**: The best-performing models underwent hyperparameter optimization to enhance predictive power.

## 3. Evaluation Metrics
- The performance of the models was assessed using several metrics:
  - **Accuracy**: The percentage of correct predictions.
  - **Precision**: The ratio of correctly predicted positive observations to the total predicted positives.
  - **Recall**: The ratio of correctly predicted positive observations to the all actual positives.
  - **F1 Score**: A weighted average of Precision and Recall.
  - **AUC-ROC**: The area under the curve of the Receiver Operating Characteristics, helping to evaluate binary classification.

## 4. SHAP Analysis
- SHAP (SHapley Additive exPlanations) values were utilized to interpret the impact of each feature on the model's predictions, providing insights into the variables contributing the most to dropout risk.

## 5. Recommendation: RandomForest_GINI
- Based on the evaluations, the Random Forest model with GINI impurity was determined to be the best overall model. It demonstrated superior performance in terms of all evaluation metrics and provided excellent interpretability through SHAP analysis.