# 🧠 Breast Cancer Detection using Machine Learning

## 📄 1. Abstract

Breast cancer is one of the most common types of cancer affecting women globally. Early detection and accurate diagnosis play a crucial role in increasing survival rates. This project uses Machine Learning techniques to detect breast cancer using the **Breast Cancer Wisconsin Diagnostic Dataset**. By training classification models such as XGBoost, we aim to predict whether a tumor is benign or malignant based on various features extracted from cell nuclei.

---

## 📊 2. Choosing the Right Dataset

We used the **Breast Cancer Wisconsin Diagnostic Dataset** from the **UCI Machine Learning Repository**. This dataset contains 569 instances with 30 numerical features, each representing various characteristics of the cell nuclei present in the image of a breast mass.

- **Target Classes**: 
  - 0 → Malignant
  - 1 → Benign
- **Features**:
  - Mean radius, texture, perimeter, area, smoothness, etc.

📌 Dataset source:
> https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

You can also load it directly using `sklearn.datasets.load_breast_cancer()`.

---

## 💻 3. Source Code

### 🔧 Tools and Libraries Used
- Python
- NumPy, Pandas
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn
- Pickle (optional for model saving)

### 🧪 Key Steps
1. Load and explore the dataset
2. Preprocess the data (scaling, train-test split)
3. Train using the **XGBoost Classifier**
4. Evaluate model performance (accuracy, confusion matrix, cross-validation)
5. (Optional) Save and load the trained model using `pickle`

### 📈 Accuracy
- **Cross-validation accuracy**: ~97%

## 📘 4. Project Documentation

### ✅ Objectives
- Detect whether a tumor is benign or malignant
- Compare cross-validation accuracy for robust model evaluation
- Understand model performance using confusion matrix and classification report

### 🧠 ML Model Used
- **XGBoost Classifier**: Selected for its high performance in classification tasks

### 📂 Directory Structure
