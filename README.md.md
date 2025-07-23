# **Loan Prediction Project**



**Objective**

To predict whether a loan application will be approved based on applicant data using logistic regression and random forest models.



**Dataset**



**File :** loan-train.csv



**Target variable :** Loan\_Status (Y = Approved, N = Not Approved)



**Features :** Gender, Married, Dependents, Education, Self\_Employed, Income, Loan Amount, Credit History, etc.



**Exploratory Data Analysis (EDA)**



* Analyzed class distribution of `Loan\_Status`
* Visualized income distributions, loan amounts, credit history
* Detected and handled class imbalance (~70:30)



&nbsp;**Data Preprocessing**



* Filled missing values using mode and median
* Encoded categorical features using Label Encoding
* Detected and mentioned class imbalance
* Applied basic scaling and transformation



**Model Building**



**Trained two models:**

* Logistic Regression
* Random Forest Classifier
* Used `train\_test\_split` for splitting data



**Evaluation Metrics**

* Classification Report: Precision, Recall, F1-score
* Confusion Matrix
* Accuracy Score



**Key Insights**

* Credit History and Income were strong predictors.
* Logistic Regression worked reasonably well.
* Random Forest helped reduce bias slightly.
* Noted class imbalance (~70% approvals), which affected minority class prediction.



**Tools \& Libraries Used**

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn
* Goggle - colab



































