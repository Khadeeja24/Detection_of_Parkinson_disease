# 🧠 Detection of Parkinson's Disease using Machine Learning

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

## 📌 Project Overview
[cite_start]Parkinson's Disease is a progressive nervous system disorder that affects movement, often starting with barely noticeable tremors. [cite_start]This project aims to develop a non-invasive diagnostic tool using Machine Learning to detect the disease in its early stages. [cite_start]By analyzing vocal patterns and biomedical voice measurements, the system can distinguish between healthy individuals and those with Parkinson's with high reliability.

[cite_start]The core objective was to benchmark multiple architectures—ranging from traditional statistical models to Deep Learning—to find the most precise method for clinical assistance.

---

## 📊 About the Dataset
[cite_start]The dataset used in this study consists of biomedical voice measurements from 31 individuals, of whom 23 have Parkinson's Disease.
* [cite_start]**Feature Set**: Includes 22 different vocal features, such as fundamental frequency (jitter, shimmer), various measures of variation in amplitude, and noise-to-harmonics ratios.
* [cite_start]**Goal**: The main target is the "status" column, which is set to 0 for healthy individuals and 1 for those with Parkinson's.
* [cite_start]**Challenge**: The dataset exhibits a class imbalance (more positive cases than negative), which was addressed using the **SMOTE** technique to ensure the model does not become biased.

---

## 💡 Key Features
* [cite_start]**Model Benchmarking:** Implemented and compared 7 models: Logistic Regression, Naive Bayes, KNN, Random Forest, SVM, XGBoost, and ANN.
* [cite_start]**Advanced Preprocessing:** Applied feature scaling and **SMOTE** to handle class imbalance and improve model generalization.
* [cite_start]**Optimized Performance:** The ANN model achieved superior results through systematic hyperparameter tuning.

---

## 📈 Performance Metrics (ANN Model)
| Metric | Score |
| :--- | :--- |
| **Accuracy** | [cite_start]97%  |
| **Precision** | [cite_start]100%  |
| **Recall** | [cite_start]97%  |
| **F1-Score** | [cite_start]0.98  |
| **ROC-AUC** | [cite_start]0.98  |

---

## 🔧 Tech Stack
* [cite_start]**Languages:** Python 
* [cite_start]**Libraries:** TensorFlow, Keras, Scikit-Learn, Pandas, NumPy, XGBoost 
* [cite_start]**Tools:** Jupyter Notebook, Git 

---

## Getting Started

### Prerequisites
To run this project, you need to have Python installed along with the following libraries:

### Installation
You can install the required packages using `pip`:

```bash
pip install -r requirements.txt
