# Handwritten Digit Recognizer

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. It includes both the model training script and a GUI for digit prediction.

## Project Structure

- `digit_recognizer.py`: Contains the code for training the digit recognition model.
- `digit_recognizer_gui.py`: Contains the code for the GUI application.
- `digit_recognizer.h5`: The trained model file.

## Running the Project
1. Train the model by running digit_recognizer.py. This will create the digit_recognizer.h5 file.
2. Launch the GUI by running digit_recognizer_gui.py.

## Libraries Used
TensorFlow/Keras
NumPy
Matplotlib
Pillow (PIL)
Tkinter

## Usage
1. Draw a digit on the canvas and click "Predict" to get the predicted digit.
2. Use the "Clear" button to reset the canvas.

## Model Details
Model Type: Sequential CNN
Epochs: 10
Loss Function: Sparse Categorical Crossentropy
Optimizer: Adam

## Requirements

To install the dependencies, run:

```bash
pip install -r requirements.txt
