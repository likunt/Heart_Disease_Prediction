# Heart_Disease_Prediction

Cardiovascular diseases are the leading cause of death globally. It is therefore necessary to identify the causes and develop a system to predict heart attacks in an effective manner. The dataset has the information about the factors that might have an impact on cardiovascular health. The target field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease. Attribute information is described below:

Data Dictionary
- age - age in years
- sex - (1 = male; 0 = female)
- cp - chest pain type 
- trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
- chol - serum cholestoral in mg/dl
- fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- restecg - resting electrocardiographic results
- thalach - maximum heart rate achieved
- exang - exercise induced angina (1 = yes; 0 = no)
- oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
- slope - the slope of the peak exercise ST segment
- ca - number of major vessels (0-4) colored by flourosopy
- thal - thalium stress result
- target - have disease or not (1=yes, 0=no) (= the predicted attribute)

### Conclusion

This project aims to study the risk of heart disease based on patients' age, sex and other clinical parameters. Data preprocessing techniques such as standardization, transformation and winsorization are applied to numerical variables, and chi-square test is applied to select related categorical features. A number of ML models (LogisticRegression, SVC, RandomForest, GaussianProcess and XGBoost) are used as baseline models. Hyperparameters are fine tuned for SVC. The test accuracy is increased from 0.8313 to 0.8442. It is also shown that without feature selection, the test accuracy drops to 0.7383.
