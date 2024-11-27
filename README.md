**Federated Learning**

This project implements a federated learning (FL) framework tailored for medical imaging datasets. The goal is to collaboratively train a robust convolutional neural network (CNN) model across multiple simulated clients (e.g., hospitals) while preserving data privacy. The project uses TensorFlow and integrates metadata from the COVID-19 Radiography Database to simulate the federated learning environment.

Results

The model's performance was evaluated on a centralized test dataset after federated training. The following metrics were achieved:

    Precision: 91.12%
    Recall: 90.83%
    F1-Score: 90.66%
    Aggregated Global Validation Loss: 0.7245
    Global Validation Accuracy: 90.83%
