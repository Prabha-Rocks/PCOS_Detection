# PCOS_Detection
 A Machine Learning-based PCOS detection system using Logistic Regression, SVM, and Random Forest. Key steps include data merging, handling null values, encoding categorical features, feature scaling, and balancing the dataset. SMOTE-ENN was explored for imbalance correction, achieving near-research-level accuracy efficiently.The project focuses on detecting Polycystic Ovary Syndrome (PCOS) using machine learning models to aid early diagnosis and timely treatment. PCOS is a prevalent hormonal disorder in women, often linked to infertility, diabetes, obesity, and cardiovascular risks. It leverages advanced data analysis and predictive modeling to improve detection accuracy.
 
# Datasets:

PCOS_infertility.csv - Data with infertility information.

PCOS_without_infertility.csv - Data without infertility information.

# Dataset source: 
https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fprasoonkottarathil%2Fpolycystic-ovary-syndrome-pcos

# Steps Involved:-

## **Data Preprocessing:**

Merging PCOS_infertility and PCOS_without_infertility datasets.

Separating numerical and categorical features.

Handling missing values and encoding categorical variables using pd.to_numeric.

## **Exploratory Data Analysis (EDA):**

Generated a Pandas Profiling HTML report for in-depth EDA.

Visualized key features, distributions, and correlations.

## **Machine Learning Models:**

Logistic Regression

Support Vector Machine (SVM)

Random Forest Classifier

## **Model Evaluation Metrics:**

Accuracy, Precision, Recall, F1 Score, and AUC-ROC.

## **Performance Comparison:**

Logistic Regression: 85.89% accuracy

SVM: 87.73% accuracy

Random Forest Classifier: 90.18% accuracy

## **Model Optimization:**

Achieved high accuracy using simpler methods compared to research papers, which used SMOTE, ENN, and Bayesian Optimization.

### **Results**

The Random Forest Classifier achieved the highest accuracy (90.18%) among all models.

Confusion matrices and ROC curves were plotted to visualize the performance of each model.

## **Repository Description:**

This repository contains a Copy_of_PCOS_Detection.ipynb (zipped file)[Main Jupyter notebook containing the entire workflow] and datasets used for PCOS detection. It walks through data preprocessing, EDA, and machine learning model training, with a focus on efficient and interpretable methods for PCOS diagnosis.

### **How to Use:**

Download and unzip the Copy of PCOS Detection.ipynb file.

Open the notebook in Jupyter or Google Colab.

Ensure the datasets (PCOS_infertility.csv and PCOS_without_infertility.csv) are in the same directory.

Run the notebook cells sequentially to reproduce the results.
