# Sanskrit Character Classification using MLP

## Project Overview

This project implements a Machine Learning based system for classifying handwritten Sanskrit/Devanagari characters using a Multi-Layer Perceptron (MLP) classifier.

The system takes handwritten character images as input, processes them into numerical feature vectors, and predicts the corresponding character class.

The trained model is capable of classifying 46 different character and digit classes.

## Objectives

- To develop a handwritten Sanskrit/Devanagari character classification system.
- To preprocess handwritten character images for machine learning.
- To train a Multi-Layer Perceptron classifier.
- To evaluate the model using standard classification metrics.
- To save the trained model for future predictions.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Dataset

The project uses a handwritten Devanagari character dataset.

The dataset contains:

- 46 character and digit classes
- Training images
- Testing images
- Grayscale handwritten character images

Each image is resized to 32 × 32 pixels and converted into a numerical feature vector containing 1024 features.

## Methodology

The project follows these major steps:

1. Dataset loading
2. Image preprocessing
3. Image resizing
4. Feature extraction
5. Label encoding
6. Train-test data preparation
7. MLP model creation
8. Model training
9. Model evaluation
10. Confusion matrix generation
11. Character prediction
12. Model and label encoder saving

## Machine Learning Model

A Multi-Layer Perceptron (MLP) classifier from Scikit-learn is used for handwritten character classification.

The model learns patterns from the training images and predicts the corresponding character class for unseen test samples.

## Model Performance

The final model produced the following evaluation results:

| Metric | Result |
|---|---:|
| Number of Classes | 46 |
| Test Samples | 13,800 |
| Training Iterations | 30 |
| Accuracy | 93.91% |
| Precision | 94.00% |
| Recall | 93.91% |
| F1-Score | 93.92% |

## Confusion Matrix

A confusion matrix was generated to analyze the classification performance of individual character classes and identify cases where visually similar characters may be confused.

## Character Prediction

The trained model was tested using an unseen test image.

The system displays:

- Input character image
- Actual character
- Predicted character
- Prediction confidence

Example prediction:

```text
Actual Character    : character_10_yna
Predicted Character : character_10_yna
Confidence          : 100.00%
