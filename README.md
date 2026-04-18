# Bi-LSTM-project-
Antioxidative Peptide Prediction Using Neural Network (LSTM)
# Antioxidative Peptide Classification using Machine Learning

Entry-level Data Science project that classifies peptides as antioxidative or non-antioxidative using a Python ML model built in Google Colab.

## Project Overview
This project trains a machine learning model to predict whether a given peptide sequence has antioxidative properties. The model is trained on labeled peptide datasets and validated on a separate test set of 30 peptides.

**Objective**: Build a classifier to distinguish antioxidative peptides from non-antioxidative peptides based on sequence data.

## Tools & Libraries
- **Python**: pandas, numpy, scikit-learn
- **Environment**: Google Colab
- **Techniques**: Data preprocessing, Feature extraction, Classification, Model validation

## Repository Contents
| File | Description |
| --- | --- |
| `peaptide_colab.ipynb` | Main Google Colab notebook with code for training and prediction |
| `final-anti-oxid.txt` | Training dataset: Peptide sequences labeled as antioxidative |
| `non-anti.txt` | Training dataset: Peptide sequences labeled as non-antioxidative |
| `30_pep.txt` | Validation dataset: 30 unlabeled peptides to test the trained model |

## How to Run
1. **Open in Colab**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VaZDD621UJDc5AliW-29G8MKWVXKGPlH)
2. **Run all cells**: The notebook loads `final-anti-oxid.txt` and `non-anti.txt` for training
3. **Test validation set**: Final cells use the trained model to predict labels for `30_pep.txt`
4. **Local option**: Download files → open `peaptide_colab.ipynb` in Jupyter/VS Code

Note: Update file paths in the notebook if running locally.

## Model Workflow
1. **Training**: Model learns from `final-anti-oxid.txt` + `non-anti.txt`
2. **Validation**: Trained model predicts which peptides in `30_pep.txt` are antioxidative

## Results
The model was evaluated on the validation set of 30 peptides.

| Metric | Score |
| --- | --- |
| Accuracy | 0.84 |
| Precision | 0.94 |
| Sensitivity / Recall | 0.87 |
| AUC | 0.923 |
| ROC AUC | 0.91 |

See the notebook output for detailed classification results on the 30 test peptides.

## About Me
Entry-level Data Scientist building proficiency in Python, ML, DL, and SAS. Connect on [LinkedIn](https://www.linkedin.com/in/hrittika-hajari-068972227).

---
*This project was created as part of my Data Science learning journey.*
