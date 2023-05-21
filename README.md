# Predictive Maintenance - Multi-Label & Multi-Class Classifications

The objective of the project is to provide a model that is capable of classifying if there's a fault in a device and afterwards classify the category of the failure that has occurred. 

The process of the project was as follows:
- I've started by explaining what is maintenance and its types
- Examples of Predictive Maintenance and its benefits
- Condition monitoring in practice (Inspection-based vs. Sensor-based)
- The Cost sensitivity in Machine Learning in the maintenance field
- I've used the data provided by UCI Machine Learning Repository
- Explored the data to gain better insights of thge data
- Created features that'll result in better machine learning models
- Created Synthetic data using SMOTETomek to balance the dataset
- Implemented pipelines that preprocess the numerical and categorical data
- For Multi-Class Classifications, I've tested the following models:
  - OutputCodeClassifier with Random Forest Classifier, Light Gradient Boosted Machine, XGBoost and CatBoost
  - OneVsRestClassifier with Random Forest Classifier, Light Gradient Boosted Machine, XGBoost and CatBoost
  - OneVsOneClassifier with Random Forest Classifier, Light Gradient Boosted Machine, XGBoost and CatBoost
- For Multi-Label Classification, I've tested the following models:
  - ClassifierChain with Light Gradient Boosted Machine, 
  - MultiOutputClassifier with Random Forest, CatBoost
-  For all the created models different evaluation metrics were applied such as Accuracy Score, F1 Score, Confusion Matrix and Precision Recall Curves.

In conclusion, seeing the impact of false negatives and false positves, the Random Forest model would make the most cost optimal model, even thou the CatBoost is a great candidate. 
