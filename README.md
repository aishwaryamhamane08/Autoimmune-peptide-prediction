# Autoimmune Peptide Prediction using Machine Learning

## Overview
This project predicts whether a peptide is autoimmune or non-autoimmune using machine learning.

## Approach
- Collected positive autoimmune peptides
- Generated negative dataset from UniProt human proteins
- Cleaned and filtered sequences
- Converted peptides into numerical format using one-hot encoding
- Trained models (Logistic Regression, Random Forest)

## Results
- Logistic Regression with class balancing gave better recall
- Demonstrated ability to detect autoimmune peptides

## Limitations
- Negative dataset is approximated
- Model may not generalize to all biological cases

## Tech Used
- Python
- Biopython
- Pandas
- NumPy
- Scikit-learn
- Pandas
- NumPy
- Scikit-learn
