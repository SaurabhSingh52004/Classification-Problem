# Diabetes Prediction using Various Machine Learning Algorithms  

## 📌 Introduction  
This project evaluates the performance of different machine learning algorithms in predicting the likelihood of diabetes. The study uses multiple classifiers to determine which algorithm provides the best prediction accuracy.  

## 📊 Dataset & Exploratory Analysis  
The dataset includes 7 predictor variables:  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

### Key Observations:  
- ✅ No duplicate records found.  
- ✅ Outliers were detected and capped to reduce their influence.  
- ✅ No missing values initially, but certain zero entries in features (like Blood Pressure, Insulin, etc.) were treated as missing.  
- ✅ Missing data was handled using imputation techniques.  

## Classifier Scores  
| Classifier                  | Accuracy Score |
|------------------------------|----------------|
| Logistic Regression          | 0.785714 |
| KNN Classifier               | 0.805195 |
| Support Vector Classifier    | 0.805195 |
| Gaussian Naive Bayes         | 0.759740 |
| Decision Trees Classifier    | 0.740260 |

## 🏆 Conclusion  
- The KNN Classifier and Support Vector Machine (SVM) achieved the highest accuracy of 80.51% and an AUC score of 86%. This indicates that the KNN and SVM are well-suited for predicting diabetes based on the features included in our dataset.
