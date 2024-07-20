# OCR Implementation using KNN, ANN, and CNN

This project demonstrates the implementation of Optical Character Recognition (OCR) using three different machine learning techniques: K-Nearest Neighbors (KNN), Artificial Neural Networks (ANN), and Convolutional Neural Networks (CNN). The objective is to compare the performance and accuracy of these models in recognizing handwritten characters.

## Introduction

Optical Character Recognition (OCR) is the process of converting images of handwritten or printed text into machine-encoded text. This project explores the implementation of OCR using three popular machine learning techniques:

1. **K-Nearest Neighbors (KNN)**
2. **Artificial Neural Networks (ANN)**
3. **Convolutional Neural Networks (CNN)**

The goal is to recognize handwritten characters and compare the performance of these models and tried implementation of ANN and KNN from scratch i.e without using libraries.

## Technologies

- **Python**: Programming language used for implementation
- **OpenCV**: Library for image processing
- **NumPy**: Library for numerical computations
- **Keras**: High-level neural networks API
- **TensorFlow**: Deep learning framework
- **scikit-learn**: Machine learning library for KNN

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Krishnapopat/Handwritten-Character-Recognition.git
    ```

## Usage

1. **Preprocess the dataset**:
    - Ensure the dataset is in the correct format and preprocess it using the provided scripts.

2. **Train the models**:
    - Train KNN, ANN, and CNN models using the training scripts provided in the `models` directory.

3. **Evaluate the models**:
    - Evaluate the performance of each model on the test dataset and compare the results.

## Dataset

The project uses a dataset of handwritten characters. You can download the dataset from [here](https://www.kaggle.com/datasets/crawford/emnist).

## Results

### K-Nearest Neighbors (KNN)
- Accuracy: 81%

### Artificial Neural Networks (ANN)
- Accuracy: 95%

### Convolutional Neural Networks (CNN)
- Accuracy: 99%

**Result** : CNN is better than ANN and KNN for digit recognition (OCR)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

