
# Breast Cancer Attributes Prediction

## Overview
This project is part of the IML Hackathon 2023, focusing on the prediction of medical characteristics of breast cancer patients based on anonymized data provided by an Israeli medical center. Our goal is to assist doctors by predicting metastasis sites and tumor sizes, thereby validating clinical decisions and reducing the need for expensive tests.

## Data
The dataset includes 65,798 anonymized records across train and test sets, each with 34 features. Files:
- `train.feats.csv`
- `test.feats.csv`
- `train.labels.0.csv` for metastases
- `train.labels.1.csv` for tumor size

## Tasks
1. **Predicting Metastases**: Predict the sites of metastases from patient data.
2. **Predicting Tumor Size**: Estimate the size of the tumor in millimeters.
3. **Unsupervised Data Analysis**: Optional analysis to discover patterns or insights in the data.

## Installation
```bash
git clone https://github.com/Asafeldman/iml-hackathon-2023
cd https://github.com/Asafeldman/iml-hackathon-2023
pip install -r requirements.txt
```

## Usage
Run the prediction models using:
```bash
python model.py
```

## Evaluation
Predictions are evaluated on:
- Micro and Macro average F1 scores for metastasis prediction.
- Mean squared error for tumor size prediction.
