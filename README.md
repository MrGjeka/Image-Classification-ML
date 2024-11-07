
# Image Classification with TensorFlow

This project demonstrates an image classification model using TensorFlow and Keras. The model is designed to classify images into two categories: "Old" and "Young". The dataset is loaded from a directory structure, preprocessed, and then used to train a convolutional neural network (CNN).

## Features

- **Data Preprocessing**: Automatically removes unsupported image formats and scales image data.
- **Model Architecture**: Utilizes a Sequential model with Conv2D, MaxPooling2D, and Dense layers.
- **Training and Evaluation**: Includes training with TensorBoard logging and evaluation using precision, recall, and accuracy metrics.
- **Visualization**: Plots training loss and accuracy over epochs.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-classification-tensorflow.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-classification-tensorflow
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset in the `Input data` directory with subdirectories for each class.
2. Run the Jupyter notebook to train the model:
   ```bash
   jupyter notebook
   ```
3. Open `Untitled1.ipynb` and execute the cells to preprocess data, train the model, and evaluate its performance.

## Results

- The model achieves a high accuracy on the test dataset, demonstrating its effectiveness in classifying images into the specified categories.
