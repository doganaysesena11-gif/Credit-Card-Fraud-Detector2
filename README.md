# Credit Card Fraud Detector (Decision Tree)

## Project Purpose
This project was created while learning classification models in Python. The goal is to detect fraudulent credit card transactions using transaction features.

## Dataset
Credit card transactions dataset including:

- Time  
- V1–V28 (PCA components)  
- Amount  
- Fraud (0 = Non-fraud, 1 = Fraud)

Dataset is highly imbalanced: 284,315 non-fraud vs 492 fraud cases.

## Data Preprocessing
- Renamed `Class` column to `Fraud`  
- Split dataset into training (90%) and test (10%) sets  
- No missing values in the dataset

## Model
- **Decision Tree Classifier** (scikit-learn)  
- `class_weight="balanced"` to handle class imbalance  
- Model trained on all numerical features

## Evaluation
- Accuracy used for evaluation  
- Confusion Matrix
- Most fraud cases are correctly detected despite imbalance

## Notes
- Linear Regression was also tested but not suitable for classification  


