# CIP-B107-CS1-AsmauDanzaria
# CIP-B107-LAB-01: AI-Assisted IP Evidence Identification and Model Evaluation

**Student:** Asmau Danzaria  
**Registration Number:** 2617285  
**Case Reference:** ICDFA-DFIR-AI-026  
**Institution:** International Cybersecurity and Digital Forensics Academy (ICDFA)

## Overview

This assessment examines the identification of potential IPv4 address candidates from synthetic configuration-related data using conventional extraction techniques and an offline machine learning classifier.

The investigation covers evidence preservation, dataset profiling, candidate extraction, IPv4 validation, model development, historical results analysis, and independent model evaluation.

## Key Results

- 229 candidate strings extracted.
- 201 syntactically valid IPv4 candidates.
- 28 invalid IPv4 candidates.
- Offline model accuracy: 97.83%.
- Precision: 97.14%.
- Recall: 100%.
- F1-score: 98.55%.

## Tools and Technologies

- Kali Linux
- Python 3.13
- pandas
- scikit-learn
- Matplotlib
- TF-IDF
- Logistic Regression
- Python `ipaddress` module

## Project Contents

The submission includes:

- Forensic investigation report (PDF)
- Python analysis scripts
- Evidence manifest and SHA-256 hashes
- Dataset profiling and candidate extraction outputs
- Model predictions and evaluation results
- Historical analysis charts
- Manual review records
- Investigation screenshots
- Executive forensic intelligence briefing

## Important Note

The supplied datasets are synthetic. The model's results are limited to the provided test data, which contains repeated prompts and training/testing overlap. Predictions require independent validation and human review.

**Assessment:** CIP-B107-LAB-01  
**Prepared by:** Asmau Danzaria
