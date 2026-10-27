# Anomaly Detection in Credit Card Transactions

## Project Overview

This project uses unsupervised machine learning to identify potentially fraudulent credit card transactions using the Isolation Forest algorithm.

The model learns patterns from transaction features without using fraud labels during training. The `Class` column is used only to evaluate the model's predictions.

## Project Objectives

- Explore transaction data and feature distributions.
- Check data types and missing values.
- Scale numerical features.
- Train an Isolation Forest model.
- Evaluate predictions using precision, recall, F1-score, and a confusion matrix.
- Analyze patterns in detected anomalies.

## Dataset

Download the Credit Card Fraud Detection dataset from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Place  `creditcard.csv` file inside the `data/` folder.

The dataset contains 284,807 transactions and 31 columns, including anonymized features, `Time`, `Amount`, and `Class`.


## Technologies Used

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

## Project Structure

```text
Anomaly Detection/
├── data/
│   └── creditcard.csv
├── notebooks/
│   └── anomaly_detection.ipynb
├── outputs/
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation and Usage

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Open the cloned project folder in VS Code.

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Download the dataset

Download the Kaggle dataset and place `creditcard.csv` inside the `data/` folder.

### 5. Run the notebook

Open `notebooks/anomaly_detection.ipynb`, select your Python virtual environment as the kernel, and run the cells in order.

## Methodology

1. Data exploration and visualization