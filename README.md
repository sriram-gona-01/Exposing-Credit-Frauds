# Exposing Credit Frauds

A machine learning project aimed at identifying fraudulent credit card applications by analyzing application records and credit history.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project focuses on detecting credit card fraud by analyzing credit application and credit record data. It uses various machine learning algorithms to classify transactions and identify fraudulent patterns. The goal is to improve the accuracy of credit fraud detection and reduce the financial impact of fraudulent activities.

## Dataset
The dataset used in this project consists of two main files:
1. `application_record.csv`: Contains personal and application information for each applicant.
2. `credit_record.csv`: Includes credit history data, such as payment status and monthly balance.

Both datasets are publicly available on Kaggle's [Credit Card Approval Prediction dataset](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction).

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/sriram-gona-01/Exposing-Credit-Frauds.git
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Jupyter notebook to explore the data, preprocess it, and build machine learning models:
   ```bash
   jupyter notebook exposing-credit-frauds.ipynb
   ```
2. Follow the instructions in the notebook to understand the data preprocessing, exploratory data analysis, and model evaluation steps.

## Exploratory Data Analysis (EDA)
The EDA section provides insights into the data distribution, missing values, and relationships between variables. Visualizations are created using libraries such as `matplotlib`, `seaborn`, and `missingno` to understand data patterns and outliers.

## Modeling
Several machine learning models are applied, including:
- Decision Trees
- Random Forest
- XGBoost
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)
- Logistic Regression

Each model is trained and evaluated based on its accuracy, precision, recall, and F1-score.

## Evaluation
The classification metrics are used to evaluate the model's performance, with a focus on identifying fraudulent transactions accurately while minimizing false positives and negatives.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
