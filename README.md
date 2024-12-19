# **Glass Type Classification Using Machine Learning**

## **Project Overview**
This project explores glass type classification using various machine learning algorithms. It involves detailed exploratory data analysis (EDA), data preprocessing, feature engineering, model training, evaluation, and visualization. The objective is to predict the type of glass based on its chemical composition.

---

## **Dataset**
The dataset used contains features related to chemical properties of glass samples and their corresponding glass types. Key features include refractive index (RI), chemical elements (Na, Mg, Al, Si, K, Ca, Ba, Fe), and the target variable, "Type of glass."

---

## **Project Workflow**

### **1. Data Exploration**
- Importing Libraries
- Loading Dataset
- Dataset Overview (shape, head, tail, datatypes)
- Checking for Null Values and Duplicates
- Statistical Summary
- Correlation Matrix and Heatmap Visualization

### **2. Data Preprocessing**
- Handling Null Values (if any)
- Scaling Features Using MinMaxScaler
- Outlier Detection and Removal Using IQR Method

### **3. Data Visualization**
- Pair Plots
- Box Plots
- Histograms and Distribution Plots
- Regression Plots

### **4. Model Training and Evaluation**
The following models were used:
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes Classifier**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Neural Network (MLPClassifier)**

### **5. Model Evaluation Metrics**
- Accuracy Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## **Results and Findings**
- The models were evaluated based on accuracy and prediction errors.
- Decision trees and random forests provided good interpretability through visualized trees.
- Neural networks achieved high accuracy after hyperparameter tuning.

---

## **Technologies Used**
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

---
