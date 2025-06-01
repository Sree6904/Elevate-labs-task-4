# Elevate-labs-task-4
AI & ML Internship - Task 4: Classification with Logistic Regression

## 🔍 Objective
The goal of this task is to implement a **binary classifier** using **Logistic Regression**, and evaluate it using common metrics such as **confusion matrix**, **precision**, **recall**, **ROC-AUC**, and **threshold tuning**.

---

## 📂 Dataset
We used the **Breast Cancer Wisconsin Dataset**, which is available directly from `sklearn.datasets`.

- **Target**: Whether a tumor is malignant (0) or benign (1)
- **Features**: Includes mean radius, texture, perimeter, area, smoothness, and other measurements from digitized images of breast masses.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 Steps Performed

1. **Loaded the Breast Cancer dataset** using `sklearn.datasets`.
2. **Split** the data into training and testing sets (80/20 split).
3. **Standardized** the features using `StandardScaler`.
4. **Trained** a Logistic Regression model on the training data.
5. **Evaluated** the model using:
   - Confusion matrix
   - Classification report (precision, recall, F1-score)
   - Accuracy
   - ROC-AUC score
6. **Plotted**:
   - Confusion matrix heatmap
   - ROC curve
   - Sigmoid function
7. **Tuned classification threshold** (e.g., 0.3) and observed its impact.

---

## 📊 Results

- **Accuracy**: ~95% (depending on split and threshold)
- **ROC-AUC Score**: > 0.98 (indicating excellent classifier performance)
- **Confusion Matrix**: Showed very few false positives/negatives

---

## 📈 Evaluation Metrics Explained

- **Precision**: How many predicted positives are actually positive.
- **Recall**: How many actual positives are correctly predicted.
- **ROC-AUC**: Area under the ROC curve — higher means better model separation.
- **Confusion Matrix**: Shows TP, FP, FN, TN counts for binary classification.
- **Sigmoid Function**: Converts linear model output to probability between 0 and 1.
- **Threshold Tuning**: Adjusting classification cut-off to control trade-offs.

---

## ✅ Conclusion
Logistic Regression is a powerful and interpretable model for binary classification problems. Proper scaling, evaluation, and threshold tuning can significantly improve results.

