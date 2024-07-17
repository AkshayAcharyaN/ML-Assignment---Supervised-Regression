# Pixel Coordinate Prediction using Deep Learning

This project uses a Convolutional Neural Network (CNN) to predict the coordinates (x, y) of a pixel with a value of 255 in a 50x50 grayscale image where all other pixels have a value of 0.

## Dataset Generation

The dataset is generated synthetically by randomly assigning the pixel with a value of 255 in each 50x50 image.

## Model

A CNN model is built using TensorFlow and Keras. The model predicts the coordinates of the pixel with value 255.

## Training

The model is trained on a dataset of 10,000 samples with an 80-20 train-test split.

## Results

The model's performance is evaluated, and predictions are visualized to compare the ground truth coordinates with the predicted coordinates.

## Dependencies

- tensorflow==2.9.0
- numpy==1.23.0
- matplotlib==3.5.2
- scikit-learn==1.1.1

## Installation

To install the dependencies, run:

```bash
pip install -r requirements.txt
