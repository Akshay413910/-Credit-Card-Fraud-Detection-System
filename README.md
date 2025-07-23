
# Fraud Detection Using Autoencoders

## Project Overview
This project applies deep learning techniques to detect credit card fraud using an unsupervised learning model based on autoencoders. It identifies outliers in transactional data by reconstructing inputs and comparing the reconstruction loss to a defined threshold.

## Features
- Preprocessing and normalization of anonymized transaction data
- Autoencoder model built with Keras and TensorFlow
- Fraud detection based on reconstruction error
- Evaluation using metrics such as confusion matrix, precision, and recall

## Technologies Used
- Python, Jupyter Notebook
- Keras, TensorFlow, Pandas, Matplotlib

## Dataset
- The dataset contains anonymized features of European credit card transactions.
- It is publicly available on Kaggle and includes both fraudulent and legitimate transactions.

## Usage
Run `fraud_detection.ipynb` in Jupyter Notebook. The model will train on normal transactions and flag anomalies.

## License
This project has been restructured for educational and demonstration purposes and does not contain copyrighted or third-party protected content.
