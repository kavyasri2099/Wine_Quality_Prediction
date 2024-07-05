# Wine_Quality_Prediction  

`Project Overview``
This project focuses on performing exploratory data analysis (EDA) and applying machine learning algorithms to classify wine type (red or white) and predict wine quality based on its physicochemical properties.  
  
`Table of Contents`  
- Dataset  
- Exploratory Data Analysis (EDA)  
- Data Preprocessing    
- Model Training and Evaluation  
- Results  
- Conclusion  
  
`Dataset`  
The dataset consists of red and white variants of the Portuguese "Vinho Verde" wine, including various physicochemical properties and sensory quality ratings.  
  
`Exploratory Data Analysis (EDA)`  
- Distribution Analysis: Examined the distribution and statistical properties of the data.  
- Missing Values: Identified and handled missing values.  
- Outliers: Detected and managed outliers.  
- Visualization: Visualized relationships between features and target variables.  
`Data Preprocessing`  
- Missing Values: Filled missing values using median values of respective columns.  
- Outliers: Handled outliers by clipping them based on wine type.  
- Normalization/Scaling: Applied normalization/scaling to features for model training.  
`Model Training and Evaluation`  
`Classification Models`  
- Algorithms: Logistic Regression, SVM, Decision Tree, Random Forest, KNN, Gaussian Naive Bayes  
- Metrics: Accuracy, Precision, Recall, F1-score  
`Regression Models`  
- Algorithms: Linear Regression, Huber Regressor, RANSAC Regressor, Theil-Sen Regressor, Decision Tree Regressor, Random Forest Regressor, SVR, KNN Regressor  
- Metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE)  
`Results`    
`Classification Results`  
- Logistic Regression: Accuracy: 97.69%, Precision: 97.84%, Recall: 99.06%, F1-score: 98.45%  
- SVM: Accuracy: 92.62%, Precision: 92.26%, Recall: 98.23%, F1-score: 95.15%  
- Decision Tree: Accuracy: 98.38%, Precision: 98.96%, Recall: 98.85%, F1-score: 98.90%  
- Random Forest: Accuracy: 99.62%, Precision: 99.58%, Recall: 99.90%, F1-score: 99.74%  
- KNN: Accuracy: 95.62%, Precision: 96.69%, Recall: 97.39%, F1-score: 97.04%  
- Gaussian Naive Bayes: Accuracy: 97.15%, Precision: 98.94%, Recall: 97.18%, F1-score: 98.05%  
`Regression Results`  
- Linear Regression: MSE: 0.5300, RMSE: 0.7280  
- Huber Regressor: MSE: 0.5373, RMSE: 0.7330  
- RANSAC Regressor: MSE: 0.7293, RMSE: 0.8540  
- Theil-Sen Regressor: MSE: 0.5428, RMSE: 0.7368  
- Decision Tree Regressor: MSE: 0.7069, RMSE: 0.8408  
- Random Forest Regressor: MSE: 0.3704, RMSE: 0.6086  
- SVR: MSE: 0.6099, RMSE: 0.7809  
- KNN Regressor: MSE: 0.6318, RMSE: 0.7948  
`Conclusion`  
The Random Forest classifier and Random Forest Regressor were the top performers for wine type classification and quality prediction, respectively, demonstrating the highest accuracy and the lowest error rates.  

