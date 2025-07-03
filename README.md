# Urban Expansion Estimator

This project uses satellite imagery from the EuroSAT dataset to classify land masses as **urban** or **non-urban** and estimate areas at risk of future urban development. It leverages both a Convolutional Neural Network (CNN) and a Random Forest classifier to compare performance across deep learning and traditional machine learning approaches.

## Features

- Binary classification: Urban vs. Non-Urban land mass detection
- CNN built using PyTorch with three convolutional layers
- Random Forest model with 100 decision trees using scikit-learn
- Performance evaluation using accuracy, F1-score, and AUC-ROC
- Visualizations for ROC curves and confusion matrices

## Results

| Model          | Accuracy | AUC-ROC | F1 (Urban) | F1 (Non-Urban) |
|----------------|----------|---------|------------|----------------|
| CNN            | 93.85%   | 0.99    | 0.88       | 0.95           |
| Random Forest  | 83.45%   | 0.93    | 0.77       | 0.87           |

## Technologies Used

- Python
- PyTorch
- scikit-learn
- NumPy, Pandas
- Matplotlib, Seaborn