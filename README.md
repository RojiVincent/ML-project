# 📈 Placement Prediction using Machine Learning

This project aims to predict whether a student will be placed based on academic performance, education background, and test scores using various supervised machine learning models. It explores the impact of preprocessing techniques like PCA, SMOTE, scaling, calibration, and threshold tuning across multiple classifiers including Logistic Regression, Decision Tree, Random Forest, SVM, Naive Bayes, KNN, and Gradient Boosting.

---

## 📁 Dataset

- The dataset contains information on **215 students** including features like:
  - Academic percentages (SSC, HSC, degree, MBA)
  - Education boards and streams
  - Work experience, test scores, and specialisation
- Target variable: `status` (Placed / Not Placed)
- No missing or duplicate records.

---

## 🔍 Project Workflow

1. **Data Exploration & Cleaning**
2. **Encoding Categorical Variables**
3. **Feature Scaling & SMOTE for imbalance**
4. **Model Training (Logistic Regression, SVM, RF, etc.)**
5. **Model Evaluation (Accuracy, F1, ROC AUC, Log Loss)**
6. **Threshold Optimization & Calibration**
7. **PCA Analysis & Comparison**

---

## 📊 Key Findings

- **Random Forest (without PCA, with calibration & threshold tuning)** performed best with:
  - **Accuracy: 0.88**, **F1-score: 0.88**, **Log Loss: 0.3255**
- **Naive Bayes with PCA** also performed well when simplicity and dimensionality reduction are preferred.
- PCA may reduce model performance if not followed by calibration/tuning.

---

## 🛠️ Technologies Used

- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Jupyter Notebook

---

