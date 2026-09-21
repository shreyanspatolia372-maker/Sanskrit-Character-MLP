# Sanskrit Character Classification using MLP

## Project Overview

This project implements a Machine Learning based Sanskrit/Devanagari handwritten character classification system using a Multi-Layer Perceptron (MLP).

The model is trained on handwritten Devanagari character images and classifies them into 46 different character and digit classes.

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

The project uses a handwritten Devanagari character dataset containing 46 classes.

The dataset includes:
- Devanagari characters
- Numerals from 0 to 9
- Training and testing images

Images are processed and converted into numerical feature vectors before being provided to the MLP model.

## Machine Learning Model

A Multi-Layer Perceptron (MLP) classifier is used for character classification.

The model is trained using the processed image data and character labels.

### Model Evaluation

The trained model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results

The final model achieved approximately:

- Accuracy: 93.91%
- Precision: 94.00%
- Recall: 93.91%
- F1-Score: 93.92%

The model was evaluated on 13,800 test samples across 46 character classes.

## Project Files

### `Sanskrit_Character_MLP.ipynb`

Google Colab/Jupyter Notebook containing the complete implementation, including:

- Dataset loading
- Data preprocessing
- Label encoding
- MLP model training
- Model evaluation
- Confusion matrix
- Character prediction
- Model saving

### `sanskrit_character_mlp.py`

Python source code containing the machine learning implementation.

## Model Output

The project can predict a handwritten Devanagari character and display:

- Actual character
- Predicted character
- Prediction confidence

## How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Upload or connect the required dataset.
3. Run the cells sequentially.
4. Train the MLP model.
5. Evaluate the model using the provided evaluation section.
6. Use the prediction section to classify characters.

## Author

**Shreyans Patolia**

B.Sc. Information Technology
