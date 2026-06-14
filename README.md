# Document Classifier — ScholarX AI/ML Track

A text document classifier trained on the 20 Newsgroups dataset
using TF-IDF vectorization and Logistic Regression.

## Categories
- comp.graphics
- rec.sport.hockey
- sci.electronics
- talk.politics.guns

## Results
- **Accuracy:** 90.57%
- **Best class:** rec.sport.hockey (F1: 0.94)
- **Confusion matrix:** Saved as confusion_matrix.png

## How to Run
pip install -r requirements.txt
python document_classifier.py

## Tech Stack
Python | scikit-learn | TF-IDF | Logistic Regression
