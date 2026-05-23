# Deep Learning and Machine Learning Projects on MNIST and CIFAR-10

This project explores multiple machine learning and deep learning approaches using the MNIST and CIFAR-10 datasets. The work includes classical machine learning models, convolutional neural networks (CNNs), residual connections, transfer learning concepts, evaluation metrics, and visualization of model behavior.

The project focuses on image classification tasks, model evaluation, and analyzing prediction performance using both traditional machine learning techniques and deep learning architectures.

---

## Datasets

### MNIST
- Handwritten digit dataset
- 28x28 grayscale images
- Used for binary classification of "lucky numbers"

### CIFAR-10
- 32x32 RGB image dataset
- 10 object classes:
  - airplane
  - automobile
  - bird
  - cat
  - deer
  - dog
  - frog
  - horse
  - ship
  - truck

---

## Project Sections

### Section 1

This section classifies whether an MNIST digit belongs to a selected set of "lucky numbers":
- 3
- 7
- 8

Implemented models:
- Logistic Regression
- Random Forest Classifier

Evaluation methods:
- 5-fold cross validation
- ROC curves
- Precision-Recall curves
- Accuracy metrics
- Confusion matrix analysis

---

### Section 2 CIFAR-10 CNN Architecture

This section builds a deep convolutional neural network for CIFAR-10 image classification using PyTorch.

Model features:
- Convolutional blocks
- Batch normalization
- Residual connections
- Max pooling
- Dropout regularization
- Data augmentation
- Cosine annealing learning rate scheduler
- Label smoothing

Data augmentation techniques:
- Random cropping
- Horizontal flipping
- Random affine transformations
- Normalization

---

### Section 3 Model Saving and Loading

The trained CNN model was:
- saved using `torch.save`
- reloaded using `load_state_dict`
- evaluated again to verify reproducibility

---

### Section 4 — Model Evaluation and Error Analysis

This section analyzes CNN prediction performance using:
- confusion matrices
- normalized confusion matrices
- most confident predictions
- common misclassification patterns
- visualization of incorrectly classified images

The project also visualizes:
- training loss
- test loss
- prediction confidence
- class-wise errors

---

## Technologies Used

- Python
- PyTorch
- torchvision
- scikit-learn
- NumPy
- matplotlib
- seaborn

---

## Deep Learning Concepts Used

- Convolutional Neural Networks (CNNs)
- Residual Connections
- Batch Normalization
- Dropout
- Learning Rate Scheduling
- Label Smoothing
- Data Augmentation
- Cross Validation
- ROC-AUC
- Precision-Recall Curves

---

## Results

### MNIST Binary Classification
The classical machine learning models achieved strong binary classification performance using:
- Logistic Regression
- Random Forests

Performance was evaluated using:
- Accuracy
- ROC-AUC
- PR-AUC

### CIFAR-10 CNN
The custom CNN achieved strong classification performance on CIFAR-10 using:
- residual blocks
- augmentation
- regularization
- learning rate scheduling

The experiments demonstrated how deeper architectures and training optimizations improve image classification accuracy.
