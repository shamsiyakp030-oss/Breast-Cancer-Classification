#  Breast Cancer Classification using Supervised Learning

##  Project Overview

This project applies multiple supervised machine learning algorithms to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer dataset from sklearn.

---

##  Objective

To evaluate and compare the performance of different classification algorithms on a real-world dataset.

---

##  Dataset

* Source: sklearn built-in dataset
* Features: 30 numerical features (e.g., radius, texture, smoothness)
* Target:

  * 0 → Malignant
  * 1 → Benign

---

##  Data Cleaning & Preprocessing

* Checked for missing values (none found)
* Converted dataset into Pandas DataFrame
* Separated features (X) and target (y)
* Split dataset into training (80%) and testing (20%)
* Applied **StandardScaler** for feature scaling

---

##  Machine Learning Models Used

### 1. Logistic Regression

* Used for binary classification
* Predicts probability using sigmoid function

### 2. Decision Tree Classifier

* Tree-based model using decision rules
* Easy to interpret

### 3. Random Forest Classifier

* Ensemble of multiple decision trees
* Reduces overfitting and improves accuracy

### 4. Support Vector Machine (SVM)

* Finds optimal hyperplane for classification
* Works well with high-dimensional data

### 5. K-Nearest Neighbors (KNN)

* Classifies based on nearest neighbors
* Simple and effective

---

##  Model Performance Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~95%     |
| Decision Tree       | ~90%     |
| Random Forest       | ~97%     |
| SVM                 | ~97%     |
| KNN                 | ~94%     |

---

##  Results

* **Best Model:** Random Forest / SVM
* **Worst Model:** Decision Tree

---

##  Visualizations

* Boxplots for outlier detection
* Histogram and scatter plots for feature analysis
* Accuracy comparison graph

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

##  How to Run

1. Clone this repository
2. Open the Jupyter Notebook
3. Run all cells step by step

---

##  Conclusion

The project demonstrates that ensemble models like Random Forest and SVM provide the best performance for classification tasks, while proper preprocessing improves model accuracy.

---

## video presentation


