# 🌸 Iris Flower Classification Project

This project explores and compares several machine learning algorithms on the well-known **Iris Dataset**, often considered the "Hello World" of machine learning. The study evaluates **Naive Bayes, Logistic Regression, SVC**, and the AutoML tool **LazyPredict** to determine the most effective modeling strategy.

---

## 🎯 Project Objective

To develop a machine learning model that accurately predicts the species of an Iris flower (Setosa, Versicolor, or Virginica) using measurements of its **sepal** and **petal** length and width.

---

## 📊 About the Dataset

The dataset contains **150 samples**, each representing one Iris flower. The features include:

* **SepalLengthCm:** Sepal length
* **SepalWidthCm:** Sepal width
* **PetalLengthCm:** Petal length
* **PetalWidthCm:** Petal width
* **Species:** Target class (*Iris-setosa*, *Iris-versicolor*, *Iris-virginica*)

---

## 🛠️ Technologies and Libraries Used

* **Python:** Main programming language
* **Pandas & NumPy:** Data manipulation and numerical operations
* **Matplotlib & Seaborn:** Data visualization (Pairplot, Scatterplot)
* **Scikit-Learn:**

  * Data preprocessing (Label Encoding, Scaling)
  * Machine learning models (GaussianNB, LogisticRegression, SVC)
* **LazyPredict:** AutoML tool for comparing multiple models quickly

---

---

## 📈 Model Results

The table below presents the accuracy scores achieved by each model:

| Model                        | Accuracy | Notes                         |
| ---------------------------- | -------- | ----------------------------- |
| **Gaussian Naive Bayes**     | **1.00** | 🏆 Excellent                  |
| **Logistic Regression**      | **1.00** | 🏆 Excellent                  |
| **SVC (RBF Kernel)**         | **0.97** | ⭐ Very Good                   |
| **LazyPredict (Top Models)** | **1.00** | 🚀 (LGBM, RandomForest, etc.) |

> **Note:** Due to the small, clean, and balanced nature of the dataset, the models achieved very high performance. The SVC model misclassified only **one sample** in the confusion matrix.

---

## 🖼️ Visualizations

Some of the analysis and visualizations included in the project:

* **Pairplot:** Shows relationships between variables and the separation of species
* **Scatterplot:** Highlights how petal length and width are strong predictors of species

```

---
