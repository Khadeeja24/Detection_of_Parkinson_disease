# Detection_of_Parkinson_disease
Parkinson’s Disease Detection using Machine Learning and Deep Learning| Implemented 7 classifiers including ANN &amp; Random Forest with hyperparameter tuning. Used SMOTE for imbalance handling and evaluated using ROC &amp; precision-recall and other metrics.

## Project Overview
This project focuses on the detection of Parkinson's Disease (PD) using machine learning and Deep learning models trained on voice recordings. Early diagnosis is crucial for managing this chronic and progressive movement disorder. We use a dataset of 195 voice samples from 31 individuals, 23 of whom have PD and 8 who are healthy controls.

The goal is to apply supervised learning techniques to predict the presence of Parkinson's Disease based on various extracted voice features.

## Dataset
The dataset, `parkinsons.csv`, contains 195 voice samples with 24 columns of various vocal feature measurements, such as frequency, jitter, and shimmer. The `status` column indicates the health status of the individual, where 1 signifies Parkinson's Disease and 0 signifies a healthy individual.

## Getting Started

### Prerequisites
To run this project, you need to have Python installed along with the following libraries:

### Installation
You can install the required packages using `pip`:

```bash
pip install -r requirements.txt
