# Internship_Mahindra
# 🧠 Machine Learning Projects – Multiple Datasets

This repository showcases the implementation of **Supervised and Unsupervised Machine Learning** techniques across multiple real-world datasets. The work was carried out during my internship at **Mahindra University**, focusing on practical applications, algorithm comparison, and insight generation.

---

## 📂 Datasets

* 🌸 **Iris Dataset** – Flower classification
* 🚗 **Car Evaluation Dataset** – Vehicle acceptability prediction
* 🌰 **Dry Bean Dataset** – Bean type identification
* 🛍️ **Mall Customer Dataset** – Customer segmentation
* 🍄 **Mushroom Dataset** – Edible vs poisonous classification
* 🍷 **Wine Quality Dataset** – Quality prediction
* 🌱 **Plant Communication Dataset** – Plant trait analysis
* 🧬 **Cancer Dataset (Denmark)** – Cancer type classification
* 🧪 **Glass Classification Dataset** – Glass type prediction
* 👗 **Fashion-MNIST Dataset** – Fashion trend analysis

---

## ⚙️ Algorithms Implemented

### 🔹 Supervised Learning

* Decision Trees
* Random Forest
* Logistic Regression
* Support Vector Machines (SVM)
* k-Nearest Neighbors (k-NN)
* Naïve Bayes
* Neural Networks

### 🔸 Unsupervised Learning

* K-Means Clustering
* Hierarchical Clustering
* DBSCAN

---

## 🔄 Project Workflow

1. **Data Collection** – Import datasets from CSV, UCI Repository, or Kaggle.
2. **Data Preprocessing** – Clean data, handle missing values, apply normalization and encoding.
3. **Exploratory Data Analysis (EDA)** – Visualize distributions, correlations, and trends.
4. **Modeling** – Apply supervised and unsupervised ML algorithms.
5. **Evaluation**

   * Classification: Accuracy, Precision, Recall, F1-score
   * Clustering: Silhouette Score
6. **Insights** – Identify patterns, relationships, and actionable outcomes.

---

## 📊 Key Results

* **Random Forest** delivered the best classification accuracy (90%+).
* **Decision Tree** performed well but struggled with overlapping classes.
* **K-Means Clustering** achieved a Silhouette Score of ~0.65.
* **DBSCAN** effectively identified outliers and niche segments.

---

## 🚀 Future Enhancements

* Integrate **brand**, **price**, and **seasonal** features in fashion datasets.
* Incorporate **Deep Learning** (CNNs) for image-based fashion analysis.
* Develop **interactive dashboards** for insights and visualization.
* Implement **feature selection** to improve accuracy and efficiency.

---

## 🛠️ Tools & Technologies

* **Language:** Python (Jupyter Notebook)
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras

---

## 🙏 Acknowledgements

* **Mahindra University** – Internship support and mentorship
* **Faculty Mentors:** Prof. Dr. Arun K. Pujari, Dr. Tauheed Ahmed, Dr. Shabnam Samima
* **Dr. Motahar Reza (GITAM)** – Project opportunity

---

## 📌 Getting Started

```bash
git clone https://github.com/your-username/ml-multiple-datasets.git
cd ml-multiple-datasets
```

---

# 🌳 Decision Tree Learning Projects

This repository also includes a dedicated module for understanding and implementing **Decision Trees** with intuitive explanations and visualizations.

## 📖 Overview

* Learn how Decision Trees work using a **5-step logical approach**.
* Visualize tree structures with Python and scikit-learn.
* Explore core concepts: Gini Index, Entropy, Overfitting, Stopping Criteria, and Tree Depth.

## 🧠 Intuition Behind Decision Trees

A **Decision Tree** is a supervised ML algorithm that splits data based on feature values, making step-by-step decisions until reaching a prediction.
*Think of it like playing “20 Questions” to arrive at the right answer.*

## ✨ Topics Covered

1. **Step-by-Step Tree Building**

   * Select best feature (Gini/Entropy)
   * Split dataset
   * Repeat recursively
   * Apply stopping rules (purity, depth, min samples, no gain)
   * Assign labels to leaf nodes
2. **Story-Based Learning**

   * “Tina the Tree” asks questions and stops when confident.
   * “Captain Tree” applies smart stopping rules.
   * “Detective Dot” classifies flowers based on petal/sepal clues.

## 📊 Dataset Used

* **Iris Dataset**

  * Features: Petal & Sepal Length/Width
  * Classes: Setosa, Versicolor, Virginica

## 🧪 Code Example

```python
from sklearn.datasets import load_iris
from sklearn.tree import DecisionTreeClassifier, plot_tree
import matplotlib.pyplot as plt

X, y = load_iris(return_X_y=True)
clf = DecisionTreeClassifier(max_depth=3)
clf.fit(X, y)

plot_tree(clf, filled=True)
plt.show()
```

---

📌 **Author:** Sofiya Sultana
📧 **Email:** [sofiyasultana208@gmail.com](mailto:sofiyasultana208@gmail.com)
💼 **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com)

---

This repository serves as both a **learning resource** and a **practical implementation** reference for machine learning techniques applied to real datasets.
