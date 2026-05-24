# handwritten-digit-classifier-cnn

A Convolutional Neural Network trained on the MNIST dataset to classify handwritten digits 0–9.

## Result
- Validation Accuracy: 99.64%
- Dataset: MNIST (70,000 images — 60,000 train, 10,000 test)

## Model Architecture
- Conv2D layers with ReLU activation
- MaxPooling for dimensionality reduction
- Dropout for regularisation
- Dense output layer with Softmax (10 classes)

## How to Run
Open the notebook in Google Colab or Jupyter and run all cells.

## Libraries Used
TensorFlow, Keras, NumPy, Matplotlib

## Reference
Built as a personal ML project to explore CNN architecture tuning and regularisation techniques.
