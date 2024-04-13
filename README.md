# CIFAR10-ResNet
Code written by Andrew Giordano and Rishie Nandhan Babu. 

Welcome to our project repository! This repository contains the codebase for our image classification project using ResNet-style convolutional neural networks on the CIFAR-10 dataset. Below, we provide an overview of the contents of this repository.

## Code Files

### 1. ResNet-Sandbox-MultipleTests.ipynb

The first notebook contains well-documented code for hyperparameter tuning to test and assess various model parameter settings and architectual designs for optimal model choice. This is where we build and evaluate models with nine hyperparameter settingsincluding number of initial filters, number of residual layers, number of residual blocks per layer, convolutional kernel size, skip connection kernel size, average pool kernel size, choice of optimizer, dropout percentage, and presence of data augmentation. 

### 2. ResNet-Sandbox-SingleTest.ipynb

In this notebook, we evaluate additional parameter settings for the final model resulting from various hyperparameter settings tested in the 'ResNet-Sandbox-MultipleTests.ipynb' notebook. This notebook focuses on fine-tuning and refining the model based on the insights gained from the initial hyperparameter tuning experiments.

### 3. Evaluate Saved Models.ipynb

The 'Evaluate Saved Models.ipynb' notebook contains code to assess models with various hyperparameter settings after training, on the test set. We load saved models and evaluate their performance on the test set to validate their effectiveness and generalization ability.

## Additional Files

### Test_Accuracy_Final.txt

This file summarizes the test accuracies on our CIFAR-10 test hold out set using various models with different hyperparameter settings evaluated from the 'ResNet-Sandbox-MultipleTests.ipynb' notebook is also summarized within the 'Test_Accuracy_Final.txt' file in our repo.

### Graphs Folder

The 'Graphs' folder contains accuracy and loss curves across epochs obtained from running the code in 'ResNet-Sandbox-MultipleTests.ipynb' for model training using various hyperparameter settings. These plots visually depict the training progress and convergence behavior of different model configurations.

Each notebook includes clear documentation and comments, and final test accuracies and number of parameters are printed for transparency. If you have any questions or feedback, feel free to reach out to us.

