# Banking Intent Classification with LoRA-RoBERTa

This project builds an end-to-end NLP system for classifying customer banking queries into 77 intent classes.

## Project Objectives

- Explore and visualize banking customer query data
- Implement PII masking for sensitive information
- Build a baseline MLP text classifier
- Finetune a RoBERTa-based transformer using LoRA
- Compare model performance using accuracy, macro F1, weighted F1, and per-class metrics

## Dataset

The project uses the Banking77 dataset, which contains customer banking queries labeled into 77 intent classes.

## Models

1. TF-IDF + MLP baseline
2. LoRA-finetuned RoBERTa classifier

## Evaluation Metrics

- Accuracy
- Macro F1-score
- Weighted F1-score
- Per-class precision, recall, and F1-score

## Project Structure

```text
.
├── banking_classification_BERT.ipynb
├── datasets/
│   ├── banking77_train.csv
│   └── banking77_test.csv
├── requirements.txt
├── README.md
└── .gitignore
