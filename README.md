
# 🩺 Diabetes Prediction 
This project focuses on predicting whether a patient is diabetic based on diagnostic health measurements. 
### 📌 Project Description
The dataset used in this project contains medical diagnostic features and a binary target variable (Outcome), where:
1 indicates the presence of diabetes
0 indicates absence.

### We perform the following steps:
- Data cleaning and missing value imputation
- Exploratory Data Analysis (EDA)
- Feature transformation and scaling
- Model training and evaluation using multiple classification algorithms
- Unsupervised clustering using KMeans for pattern discovery

### 📊 Dataset Features
The dataset (diabetes.csv) includes 768 patient records and the following features:
- Pregnancies – Number of times pregnant
- Glucose – Plasma glucose concentration
- BloodPressure – Diastolic blood pressure (mm Hg)
- SkinThickness – Triceps skinfold thickness (mm)
- Insulin – 2-Hour serum insulin (mu U/ml)
- BMI – Body Mass Index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction – A function which scores likelihood of diabetes based on family history
- Age – Age in years
- Outcome – Target variable (1: diabetic, 0: non-diabetic)

### ⚙️ Machine Learning Models Used
✅ Supervised Learning:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest ✅ (Best-performing)
- Gradient Boosting

### 🔄 Unsupervised Learning:
- KMeans Clustering with n_clusters=3 for pattern discovery and grouping

### ✅ Results
Among all tested models, the best performance was achieved by:
#### 👉 Random Forest Classifier with Accuracy: 81.2%
The model showed high effectiveness in identifying both diabetic and non-diabetic cases, making it a strong candidate for real-world deployment with further hyperparameter tuning and validation.


### 🧾 Requirements
You can install dependencies using pip:
pip install pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels
