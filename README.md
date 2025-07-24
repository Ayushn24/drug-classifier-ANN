
# Drug Classification using Neural Networks

This project uses a neural network model to classify drugs based on features such as Age, Sex, Blood Pressure, Cholesterol, and Sodium-to-Potassium ratio. The dataset is publicly available on Kaggle.

## 🔗 Dataset

**Kaggle Dataset:** [Drug Classification by Pratham Tripathi](https://www.kaggle.com/datasets/prathamtripathi/drug-classification)

The dataset contains the following features:
- Age
- Sex
- Blood Pressure (BP)
- Cholesterol
- Na_to_K (Sodium-to-Potassium ratio)
- Drug (Target label: DrugA, DrugB, DrugC, DrugX, DrugY)

## 🧠 Model Description

A simple Artificial Neural Network (ANN) was built using TensorFlow/Keras. The model architecture included several dense layers with ReLU activation and a softmax output layer for multi-class classification.

## 🎯 Results

- **Test Accuracy**: 93%
- **Misclassifications**: Only 2 samples were misclassified on the test set.

## 📁 Files

- `drug_classifier.ipynb`: Training and evaluation notebook.
- `README.md`: This file.
