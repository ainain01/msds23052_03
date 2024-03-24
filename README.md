# msds23052_03
Task 1: Training a CNN on MNIST
*Description
In Task 1, we train a CNN on the MNIST dataset to classify handwritten digits.
*Instructions
Run msds23052_03_task1.py to train the model.
The trained model will be saved as mnist_cnn_model.pth.

TAsk2A&2B : Image Classification with VGG16
This repository contains code for fine-tuning the VGG16 model on a custom image classification dataset.
*Transformations
Images are resized to (224, 224) pixels.
Images are converted to PyTorch tensors.
Images are normalized with mean [0.485, 0.456, 0.406] and standard deviation [0.229, 0.224, 0.225].
*Instructions
Specify the root directory where your dataset is located in the root_dir variable.
Run msds23052_03_task2.py to train the model.
or
Run msds23052_03_task2b.py to train the model for fine tuning.
The trained model will be saved as vgg16_model.pth.
