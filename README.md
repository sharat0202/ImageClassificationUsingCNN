# Fashion MNIST Classification using CNN

This project aims to classify images from the Fashion MNIST dataset using a Convolutional Neural Network (CNN) model. The dataset consists of 10 categories of fashion items, such as T-shirts, trousers, dresses, and shoes.

### Dataset

    Fashion MNIST: A dataset of 28x28 grayscale images, with 60,000 training images and 10,000 test images. It contains 10 categories:
        T-shirt/top
        Trouser
        Pullover
        Dress
        Coat
        Sandal
        Shirt
        Sneaker
        Bag
        Ankle boot

### Model Architecture

The CNN model follows the structure:

    Conv Layer: Convolutional layer with filters applied to extract features.
    Conv Layer: Second convolutional layer to deepen feature extraction.
    Max Pooling Layer: Reduces dimensionality and captures important information.
    Conv Layer: Third convolutional layer for further feature extraction.
    Conv Layer: Fourth convolutional layer to capture more complex patterns.
    Max Pooling Layer: Another max pooling layer to reduce spatial dimensions.
    Flatten: Flattens the multidimensional output from the convolutional layers.
    Global Average Pooling: Reduces the feature map to a single value per feature map, improving model efficiency.

### Goal

The goal of this project is to accurately classify the fashion items into their respective categories using the designed CNN model.