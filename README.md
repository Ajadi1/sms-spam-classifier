# SMS Spam Classifier

Fine-tuning a pre-trained DistilBERT model for binary SMS spam classification using Hugging Face Transformers and PyTorch.

## Project Overview
This project classifies SMS messages as either:
- Spam
- Ham

The model used is `distilbert-base-uncased`, fine-tuned on the SMS Spam Collection dataset.

## Tech Stack
- Python
- Google Colab
- Hugging Face Transformers
- PyTorch
- Scikit-learn

## Files
- `spam_classifier.ipynb` - notebook containing preprocessing, training, and evaluation
- `project_report.docx` - written report for the course term project

## Model
- DistilBERT (`distilbert-base-uncased`)

## Task
Binary text classification:
- 0 = Ham
- 1 = Spam

## Dataset
SMS Spam Collection dataset

## How to Run
1. Open the notebook in Google Colab
2. Install required packages
3. Run all cells in order
4. Train and evaluate the model

## Expected Performance
- Accuracy: ~98–99%
- Spam F1: ~95–97%

## Author
OPEYEMI AJADI
