# Wine_Quality_Prediction  
  
`Overview`:  
This project aims to predict the quality of wine using a variety of machine learning algorithms. The dataset used contains several chemical properties of wine and their respective quality ratings.  
  
`Data Preprocessing`:  
`Data Imputation`: Missing values were handled using the K-Nearest Neighbors (KNN) imputer. The number of neighbors was chosen as the square root of the number of data points.  
`Feature Scaling`: RobustScaler was used for data transformation to handle outliers effectively.  
`Feature Selection`: Important features were identified using a Decision Tree classifier, and visualized using a bar plot of feature importances.  
  
`Modeling`  
Several machine learning models were trained and evaluated:  
  
- K-Nearest Neighbors (KNN):  
Used with distance weighting and Minkowski metric.  
- Decision Tree:  
Built with a maximum depth of 3 and Gini impurity as the criterion.  
- Logistic Regression:  
Employed with a maximum iteration of 1000.  
- Gaussian Naive Bayes:  
Applied for probabilistic classification.  
- Random Forest:  
Utilized as an ensemble learning method.  
- Handling Imbalanced Data  
`ADASYN`: Adaptive Synthetic Sampling was used to handle class imbalance by generating synthetic samples for the minority class.  
  
`Evaluation Metrics`  
The models were evaluated based on the following metrics:  
  
`Accuracy`: Proportion of correctly predicted instances.  
`Precision`: Ratio of true positive predictions to the total predicted positives.  
`Recall`: Ratio of true positive predictions to all actual positives.  
`F1-Score`: Harmonic mean of precision and recall.  
  
`Visualization`  
- Box Plots: Visualized the distribution of numerical features.  
- Feature Importances: Displayed the importance of features using a bar plot.  
- Performance Metrics: Bar plot comparing accuracy, precision, recall, and F1-score of different models.  
- Quality Distribution: Histogram showing the distribution of wine quality ratings.  
    
`Results`  
The Random Forest classifier achieved the highest performance across most metrics, with an accuracy of approximately 98.2%.  
  
`Key Features`  
The most influential features in predicting wine quality were identified as:  
  
- Alcohol  
- pH  
- Residual Sugar  
- Chlorides  
- Sulphates  
- Total Sulfur Dioxide  
    
`Conclusion`  
This project demonstrates the application of various machine learning techniques for wine quality prediction. The results indicate that ensemble methods like Random Forests can provide robust and accurate predictions. The analysis also highlights the importance of handling missing values, scaling data, and addressing class imbalance for improving model performance.  
