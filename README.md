# MSDS23052_03

## Task 1: Training a CNN on MNIST

### Description
In Task 1, we train a Convolutional Neural Network (CNN) on the MNIST dataset to classify handwritten digits.

### Instructions
1. Run `msds23052_03_task1.py` to train the model.
2. The trained model will be saved as `mnist_cnn_model.pth`.

---

## Task 2A & 2B: Image Classification with VGG16

### Description
This repository contains code for fine-tuning the VGG16 model on a custom image classification dataset.

### Transformations
- Images are resized to (224, 224) pixels.
- Images are converted to PyTorch tensors.
- Images are normalized with mean [0.485, 0.456, 0.406] and standard deviation [0.229, 0.224, 0.225].

### Instructions
1. Specify the root directory where your dataset is located in the `root_dir` variable.
2. Run `msds23052_03_task2.py` to train the model.
   or
   Run `msds23052_03_task2b.py` to train the model for fine-tuning.
3. The trained model will be saved as `vgg16_model.pth`.

