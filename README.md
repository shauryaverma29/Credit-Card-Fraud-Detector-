# Credit Card Fraud Detector (CCF)

A machine learning system to detect fraudulent transactions in real-time with risk scoring.

## Description

Credit card fraud is a critical issue due to the extremely imbalanced nature of transaction data, where fraudulent cases are rare but impactful.
CCF solves this by using machine learning models with imbalance handling techniques to accurately detect fraud while minimizing false positives. It also provides an interpretable fraud risk score for each transaction.

---

## Features

* Detects fraudulent transactions with ~90%+ precision
* Improves fraud recall by ~30–40% using SMOTE
* Fraud risk scoring system (0–100 scale)
* Real-time and batch prediction via Streamlit app
* Handles highly imbalanced datasets effectively

##  Tech Stack

* Python
* Pandas
* Scikit-learn
* XGBoost
* Streamlit

##  Dataset

* Source: Kaggle – Credit Card Fraud Detection Dataset
* Contains anonymized transaction features with a highly imbalanced distribution (fraud vs non-fraud)

## Installation / Setup

```bash
git clone <repo-link>
cd CCF
pip install -r requirements.txt
streamlit run app.py
```
##  Usage

* Input a single transaction or upload a CSV file
* Model predicts whether the transaction is Fraud or Not Fraud
* Displays a fraud risk score (0–100)
* Visual insights for better interpretation

##  Project Structure

```
├── data/
├── models/
├── app.py
├── train.py
└── README.md
```
##  Results / Output

* High overall accuracy (~99%)
* Improved fraud detection recall (~30–40%)
* Precision-focused evaluation due to class imbalance

##  Future Improvements

* Deploy on cloud (AWS/GCP)
* Add deep learning models
* Improve real-time prediction latency
* Enhance explainability with SHAP

## Author

**Shaurya Verma**
GitHub / LinkedIn (add your links)
