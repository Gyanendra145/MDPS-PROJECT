# MDPS-PROJECT

# Multimorbidity Disease Prediction System

This repository contains the implementation of a Multimorbidity Disease Prediction System utilizing machine learning algorithms. The goal of this project is to provide early diagnosis of diseases such as **Diabetes**, **Heart Disease**, **Parkinson’s Disease**, **Cancer**, and **Liver Disease**. The system employs a combination of machine learning models and ensemble learning techniques to improve prediction accuracy, with a special focus on **Random Forest**, **K-Nearest Neighbors (KNN)**, **Naive Bayes**, **Decision Tree**, and **Gradient Boosting**.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Results](#results)
- [Future Scope](#future-scope)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Early diagnosis is critical in healthcare, as it can help reduce disease severity and improve patient outcomes. This project aims to facilitate the prediction of multiple diseases simultaneously using machine learning algorithms and ensemble techniques such as Hard Voting and Gradient Boosting. By integrating data from sources such as electronic health records (EHRs), patient-generated health data (PGHD), biomedical imaging, and genomic data, this system provides accurate predictions, leading to better healthcare decisions.

## Features

- **Multimorbidity Prediction**: Predicts the likelihood of multiple diseases including diabetes, heart disease, Parkinson’s, cancer, and liver disease.
- **Machine Learning Algorithms**: Incorporates popular machine learning models such as Random Forest, KNN, Decision Tree, and Naive Bayes.
- **Ensemble Learning**: Utilizes Hard Voting and Gradient Boosting to improve prediction accuracy.
- **Data Integration**: Integrates multiple data sources like EHRs, PGHD, genomic data, and biomedical imaging for comprehensive predictions.
- **Customizable**: Easy to add more diseases or prediction models based on requirements.

## Technologies Used

- **Python**: Main programming language for the implementation.
- **Machine Learning Libraries**: `scikit-learn`, `pandas`, `numpy`, `matplotlib`.
- **Ensemble Learning**: Hard Voting and Gradient Boosting techniques.
- **Data Preprocessing**: Imputation of missing values, feature selection, and normalization.

## Installation

Clone the repository:

git clone https://github.com/Gyanendra145/MDPS-PROJECT

Navigate to the project directory:
cd MDPS-PROJECT

Create and activate a virtual environment (optional but recommended):

python3 -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate


##Usage
Prepare the Dataset
The project requires medical datasets such as EHRs, PGHD, biomedical images, or genomic data. Ensure your dataset is properly formatted and placed in the dataset/ directory.

Data Sources
The model uses diverse data sources to improve prediction accuracy:

Electronic Health Records (EHRs): Containing medical histories and diagnoses.
Patient-Generated Health Data (PGHD): Data from wearable devices and smartphone apps.
Biomedical Imaging: X-ray, MRI, and other imaging data.
Genomic Data: Data from DNA/RNA sequencing.

Methodology
The following machine learning models are utilized in the prediction system:

Random Forest: Ensemble of decision trees trained on different subsets of data and features.
K-Nearest Neighbors (KNN): Distance-based model that uses the k nearest neighbors to classify data points.
Decision Tree: A flowchart-like model that makes decisions based on features.
Naive Bayes: A probabilistic classifier based on Bayes' theorem.
Hard Voting: An ensemble method combining the predictions from multiple models.
Gradient Boosting: Boosts model accuracy by sequentially improving misclassified cases.


Results
In our experiments, ensemble learning outperformed individual machine learning models in predicting multiple diseases:

Diabetes: Gradient Boosting achieved 79.88% accuracy.
Heart Disease: Gradient Boosting achieved 88.52% accuracy.
Parkinson’s Disease: Gradient Boosting achieved 82.0% accuracy.
Cancer: Gradient Boosting achieved 98.12% accuracy.
Liver Disease: Gradient Boosting achieved 79.66% accuracy.

Future Scope
Expand the Model: The system can be expanded to include more diseases.
Cost-Effectiveness: Plan to incorporate economic factors and provide estimates of treatment costs.
Deep Learning: Exploring advanced techniques such as deep learning to further enhance predictive accuracy.
Real-time Implementation: Implement real-time disease predictions using wearable devices and live data streams.


