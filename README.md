# Saudi Riyal Classifier
## Task Overview:
#In this project, you’ll build an image classification model using a Convolutional Neural Network (CNN) to recognize Saudi currency images based on their visual appearance.
## The dataset is available on Kaggle:
####  https://www.kaggle.com/datasets/gfbati/alfloos
# It includes images of the following currency denominations: 5,50, 100, 200, 500.
## Model & Training
# The model was built from scratch using a custom Convolutional Neural Network (CNN) architecture. I experimented with different layers, filter sizes, and activation functions to achieve the best performance.
# To improve the model’s generalization and robustness, I applied several data preprocessing and augmentation techniques, including:
# Data Augmentation: Rotation, Contrast, brightness adjustments to increase dataset variety.
# Normalization: All images were resized to a consistent shape and pixel values were scaled to the range [0, 1].
## Demo Interface
# To make the model accessible to everyone, I created an interactive Gradio web interface where users can upload images of Saudi Riyal banknotes and get instant classification results.
## Try it here:
# https://huggingface.co/spaces/hanin77/saudi-riyal-classifie
