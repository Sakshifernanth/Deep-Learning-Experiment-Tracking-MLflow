# Deep Learning Experiment Tracking and Model Management Using MLflow

An end-to-end MLOps mini-project demonstrating experiment tracking, hyperparameter comparison, model logging, model registration, and version management using MLflow and TensorFlow.

## Project Overview

Machine learning development involves more than training a model. Experiments must be tracked, performance must be compared, and trained models must be stored and managed systematically.

This project demonstrates an MLOps workflow using a Convolutional Neural Network (CNN) trained on the MNIST handwritten digit dataset.

The primary focus is on **MLOps practices**, with deep learning serving as the supporting application.

## Objectives

- Track multiple deep learning experiments using MLflow.
- Log hyperparameters, evaluation metrics, and model artifacts.
- Compare experiment performance.
- Identify and register the best-performing model.
- Manage model versions and metadata.
- Retrieve the registered model for inference.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| TensorFlow / Keras | CNN model development |
| MLflow | Experiment tracking and model management |
| NumPy | Numerical operations |
| Pandas | Experiment result analysis |
| Matplotlib | Data visualization |
| Google Colab | Development environment |
| GitHub | Version control and project hosting |

## Project Workflow

1. Load and preprocess the MNIST dataset.
2. Build a CNN image classification model.
3. Train three experiments with different hyperparameter configurations.
4. Track parameters, metrics, and model artifacts using MLflow.
5. Compare the experiment results.
6. Register the best-performing model in MLflow Model Registry.
7. Add model descriptions and metadata tags.
8. Load the registered model and perform inference.

## Experiment Configurations

| Experiment | Learning Rate | Epochs |
|---|---:|---:|
| CNN_Experiment_1 | 0.001 | 3 |
| CNN_Experiment_2 | 0.0005 | 3 |
| CNN_Experiment_3 | 0.001 | 5 |

## Results

| Experiment | Test Accuracy | Test Loss |
|---|---:|---:|
| CNN_Experiment_1 | 98.37% | 0.0488 |
| CNN_Experiment_2 | 98.43% | 0.0490 |
| CNN_Experiment_3 | **98.88%** | **0.0318** |

**Best Experiment:** CNN_Experiment_3

**Registered Model:** MNIST_CNN_Best_Model

**Model Version:** 1

## Model Management

The best-performing model was registered using MLflow Model Registry.

- Model status: READY
- Version: 1
- Architecture: CNN
- Dataset: MNIST
- Source experiment: CNN_Experiment_3

## Inference Demonstration

The registered model was successfully loaded from the MLflow Model Registry and used to predict a handwritten digit.

- Predicted digit: 7
- Actual digit: 7
- Prediction confidence: 99.99%

## Key MLOps Concepts Demonstrated

- Experiment tracking
- Hyperparameter logging
- Metric logging
- Model artifact management
- Experiment comparison
- Model registry
- Model version management
- Model retrieval and inference

## Future Improvements

- Implement dataset version control using DVC.
- Add automated experiment comparison.
- Integrate model deployment through an API.
- Implement automated model evaluation and monitoring.

## Author

BCA – Artificial Intelligence and Machine Learning Student

Academic MLOps Mini-Project
