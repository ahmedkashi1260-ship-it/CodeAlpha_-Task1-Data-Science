# CodeAlpha_-Task1-Data-Science
# 🌸 Iris Flower Classification with Logistic Regression

A end-to-end Machine Learning pipeline in Python that classifies Iris flowers into three species (*Iris setosa*, *Iris versicolor*, and *Iris virginica*) based on their sepal and petal measurements.

---

## 📌 Project Overview

This project uses scikit-learn to build a machine learning workflow for multi-class classification. The pipeline includes:
* **Data Processing & Exploration**: Loading and inspecting feature distribution and missing values.
* **Feature Scaling**: Standardizing features using `StandardScaler` inside a scikit-learn `Pipeline`.
* **Model Training**: Logistic Regression optimized for multi-class prediction.
* **Model Evaluation**: Metrics including Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix visualization.
* **Inference**: Making predictions on unseen flower measurements.

---

## 🛠️ Dataset

The dataset used is the classic **Iris Dataset** (`Iris.csv`). It contains **150 instances** (50 per species) with the following features:

| Feature Name | Description | Unit |
| :--- | :--- | :--- |
| `SepalLengthCm` | Length of the flower's sepal | cm |
| `SepalWidthCm` | Width of the flower's sepal | cm |
| `PetalLengthCm` | Length of the flower's petal | cm |
| `PetalWidthCm` | Width of the flower's petal | cm |
| **`Species`** | **Target Class**: `Iris-setosa`, `Iris-versicolor`, `Iris-virginica` | Categorical |

---

## 💻 Tech Stack & Dependencies

* **Python 3.8+**
* **Pandas**: Data manipulation and structure
* **Matplotlib**: Visualizing the confusion matrix
* **Scikit-Learn**: Model building, evaluation, and scaling pipeline

### Installation

Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/your-username/iris-classification.git](https://github.com/your-username/iris-classification.git)
cd iris-classification
pip install pandas matplotlib scikit-learn
