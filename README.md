# Histopathologic Cancer Detection

This project addresses the Kaggle *Histopathologic Cancer Detection* challenge.
The task is a binary image classification problem to detect metastatic cancer
in 96×96 histopathology image patches.

The dataset is derived from the PatchCamelyon (PCam) benchmark.
Model performance is evaluated using AUC-ROC.

## Approach
- Exploratory Data Analysis (class distribution, data quality checks, sample visualization)
- CNN-based models trained from scratch due to environment constraints
- Comparison between a custom SimpleCNN and ResNet18
- Model selection based on validation AUC

## Results
- Best validation AUC ≈ 0.905 (ResNet18, trained from scratch on a reduced subset)
- Early overfitting observed due to limited data and no strong augmentation

## Files
- `notebook.ipynb`: full analysis, training, evaluation, and submission generation

## Competition
Kaggle: Histopathologic Cancer Detection
