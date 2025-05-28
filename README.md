Handwritten Digit Classification using ANN

This project demonstrates a simple yet powerful implementation of **Artificial Neural Networks (ANNs)** to classify handwritten digits (0–9). The model is trained on the **MNIST** dataset, one of the most popular datasets in machine learning and computer vision.


Dataset

We use the [MNIST dataset](http://yann.lecun.com/exdb/mnist/), which consists of:
- 60,000 training images
- 10,000 testing images
- Grayscale, 28x28 pixels
- Labels: digits from 0 to 9

 How It Works

The ANN model is built using **Keras** and trained to recognize patterns in handwritten digits. Once trained, it can generalize and classify new, unseen digit images.

### Architecture:
- **Input Layer**: 784 neurons (28x28 pixels flattened)
- **Hidden Layers**: 1 or more Dense layers with ReLU activation
- **Output Layer**: 10 neurons (softmax for 10 digit classes)

# Credit to CampusX Learning 
