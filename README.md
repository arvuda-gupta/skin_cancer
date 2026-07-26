# Skin Cancer Detection using Deep Learning (CNN)

A deep learning-based image classification project that detects whether a dermoscopic skin lesion is **Benign** or **Malignant** using a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras.

## Project Overview

This project implements an end-to-end deep learning pipeline for binary skin cancer classification. It includes data preprocessing, image augmentation, CNN model development, training, evaluation, and prediction on unseen skin lesion images. The model is trained to distinguish between benign and malignant lesions, demonstrating the application of computer vision in medical image analysis.

## Features

- Binary classification (Benign vs Malignant)
- Image preprocessing and normalization
- Data augmentation
- Custom CNN architecture
- Early Stopping & ReduceLROnPlateau callbacks
- Model evaluation using Accuracy, Confusion Matrix, and Classification Report
- Prediction on custom images
- Saved trained model for future inference

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```
Skin-Cancer-Detection/
│── skincancer.ipynb
│── README.md
│── requirements.txt
│── dataset/
│── model/
```

## Workflow

1. Load and preprocess the skin lesion dataset.
2. Apply image augmentation and normalization.
3. Build a Convolutional Neural Network (CNN).
4. Train the model with Early Stopping and learning rate scheduling.
5. Evaluate performance using classification metrics.
6. Save the trained model.
7. Predict whether new skin lesion images are benign or malignant.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Skin-Cancer-Detection.git
cd Skin-Cancer-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook skincancer.ipynb
```

Run all notebook cells to train the model and make predictions.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Sample Output

```text
Prediction: Benign
```

or

```text
Prediction: Malignant
```

## Disclaimer

This project is intended for educational and research purposes only and should not be used as a substitute for professional medical diagnosis.

## Author

**Arvuda Gupta**

If you found this project useful, consider giving it a star.
