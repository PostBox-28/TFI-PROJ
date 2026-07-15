# TFI-PROJ
heart diseas prediction to prevent the heart problems
# Loan Eligibility Prediction System

This project predicts whether a loan application should be approved or rejected using Machine Learning. It analyzes applicant information such as income, credit history, loan amount, and other details to make predictions.

## Project Structure

```text
loan-eligibility-predictor/

data/
    loan_data.csv

output/
    confusion_matrix.png
    roc_curve.png
    classification_report.txt
    loan_predictions.csv

loan_predictor.py
README.md
requirements.txt
```

## Requirements

Python 3.x

pandas

numpy

scikit-learn

matplotlib

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python loan_predictor.py
```

## Output

confusion_matrix.png - Shows model performance.

roc_curve.png - Shows ROC curve.

classification_report.txt - Displays accuracy, precision, recall, and F1-score.

loan_predictions.csv - Stores loan approval predictions.

## Author

Machine Learning Classification Project for academic purposes.
