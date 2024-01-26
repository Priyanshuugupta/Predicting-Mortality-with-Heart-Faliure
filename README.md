# Predicting Mortality with Heart Failure in ICU Patients

## Project Overview

This project aims to develop a predictive model for mortality in ICU patients with heart failure. The goal is to leverage machine learning techniques to analyze relevant clinical data and make accurate predictions regarding the likelihood of mortality during the ICU stay.

## Table of Contents

- [Background](#background)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Background

Patients admitted to the ICU with heart failure often face critical conditions, and predicting mortality is crucial for making informed decisions about treatment strategies. This project addresses the need for an accurate mortality prediction model to assist healthcare professionals in identifying high-risk patients early in their ICU stay.

## Dataset

The dataset used for this project contains clinical data from ICU patients with heart failure. The data includes various features such as vital signs, laboratory results, and patient demographics. The dataset has been anonymized and preprocessed for privacy and confidentiality.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/heart-failure-prediction.
   
Usage
The project is structured as follows:

src/: Contains the source code for data preprocessing, model training, and evaluation.
data/: Holds the dataset used for training and testing the model.
notebooks/: Jupyter notebooks for exploratory data analysis and model development.

Data Preprocessing
Before training the model, it's essential to preprocess the data. The preprocessing steps include handling missing values, scaling features, and encoding categorical variables. Refer to the src/preprocess.py script for details.

Evaluation
The model's performance is evaluated using metrics such as accuracy, precision, recall, and ROC-AUC. The evaluation results can be found in the results/ directory.

Results
From the comparision of different models we can say the Logistic Regression model is the best for prediction for our dataset along the with the accuracy, the metrics like precision, recall were also best for this model when compared to the other.

Contributing
If you wish to contribute to the project, please follow the contributing guidelines.
