#  Task 4: Classification with Logistic Regression

## Objective
Build a **binary classifier** to predict whether a tumor is **benign or malignant** using **Logistic Regression**.

##  Tools Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

##  Dataset
**Dataset:** [Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  
**Target Column:** `diagnosis`  
- **M** → Malignant  
- **B** → Benign  

##  Steps Followed
1. **Import and Load Data** – Loaded dataset into a pandas dataframe.  
2. **Preprocess Data** – Removed unnecessary columns, converted labels to numeric, and standardized features.  
3. **Split Data** – Divided the dataset into training and testing sets.  
4. **Train Model** – Applied Logistic Regression from scikit-learn.  
5. **Evaluate Model** – Used confusion matrix, precision, recall, F1-score, and ROC-AUC.  
6. **Tune Threshold** – Adjusted classification threshold to analyze trade-offs between precision and recall.  
7. **Explain Sigmoid Function** – Explained how logistic regression converts linear output into probabilities between 0 and 1.

##  Results
- The model achieved **high accuracy (around 95–98%)**.  
- **ROC-AUC score** showed strong classification performance.  
- Logistic Regression successfully distinguished between **malignant** and **benign** tumors.

##  Conclusion
- Logistic Regression is a **simple yet powerful model** for binary classification.  
- Understanding the **sigmoid function** and **threshold tuning** improves interpretability.  
- This model demonstrates how machine learning can help in **early detection of breast cancer**.
