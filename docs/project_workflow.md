
# Project Workflow

## 1. Dataset
The MNIST handwritten digit dataset was used for CNN-based image classification.

## 2. Data Preprocessing
- Loaded training and testing images.
- Normalized pixel values.
- Reshaped images for CNN input.

## 3. Model Development
A Convolutional Neural Network (CNN) was developed using TensorFlow and Keras.

## 4. Experiment Tracking
MLflow was used to track:
- Learning rate
- Number of epochs
- Batch size
- Optimizer
- Training and validation metrics
- Test accuracy and loss
- Model artifacts

## 5. Experiment Comparison
Three experiments were conducted with different configurations to evaluate model performance.

## 6. Model Registration
The best-performing model was registered in the MLflow Model Registry as `MNIST_CNN_Best_Model`, version 1.

## 7. Model Inference
The registered model was loaded and tested on an unseen MNIST sample.

## 8. Best Result
- Best experiment: CNN_Experiment_3
- Test accuracy: 98.88%
- Test loss: 0.0318
- Sample prediction: 7
