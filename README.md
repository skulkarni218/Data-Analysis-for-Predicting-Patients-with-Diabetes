# Data-Analysis-for-Predicting-Patients-with-Diabetes
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

For predicting if a person has Diabetes or not, I have used Pandas, Numpy, Matplotlib and Seaborn for Exploratory Data Analysis and have used different libraries of SciKit for implementing Machine Learning algorithms. The machine learning algorithms used are - Logistic Reagression, Random Forest Classifier and Support Vector Machine.

From the exploratory analysis I found out that the distribution of the target column - Outcome was biased. Hence, predicting with 100% accuracy was impossible. Furthermore, factors such as Glucose and Age had a lot of impact on the target column - Outcome. Drilling down further, helped me understand that patients with diabetes have high Glucose in their body irrespective of the Age.

The results of Machine Learning algorithms can be seen below:
| Model Type  | False Prediction | F-1 Score | Accuracy | 
| ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 36  | 0.78  | 0.86  | 
| Random Forest Classifier with default parameters  | 37  | 0.73  | 0.85  |
| Random Forest Classifier with some tweeking  | 31  | 0.75  | 0.88  |
| Random Forest Classifier with best parameters  | 36  | 0.73  | 0.86  |
| Support Vector Classifier with default parameters  | 87  | 0.52  | 0.66  |
| Support Vector Classifier with best parameters  | 39  | 0.76  | 0.85  |
