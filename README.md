Recognize a Digit using Machine Learning

1.Overview:- 
This project uses TensorFlow and the MNIST dataset to recognize handwritten digits (0–9).
The model is built using a simple neural network with one hidden layer and trained to achieve high accuracy on test data.

2.Dataset:-
MNIST dataset: A collection of 70,000 grayscale images of handwritten digits (28×28 pixels).

60,000 images are used for training, and 10,000 images are used for testing.

3.Model Architecture:-
Flatten Layer: Converts 28×28 pixel images into a 1D array (784 values).

Dense Layer (128 neurons): Fully connected layer with ReLU activation.

Dropout Layer (20%): Prevents overfitting by randomly turning off neurons during training.

Dense Layer (10 neurons): Output layer with Softmax activation for classification into 10 digit classes.

##Steps in the Code:-
1.Import Libraries: TensorFlow, Keras, NumPy, Matplotlib.

2.Load Data: Import MNIST dataset from Keras.

3.Normalize Data: Scale pixel values to range [0,1].

4.Build Model: Define the sequential neural network.

5.Compile Model: Use Adam optimizer and sparse categorical crossentropy loss.

6.Train Model: Fit on training data for 5 epochs.

7.Evaluate Model: Test accuracy on test dataset.

8.Prediction: Show example image and predict its label.

Requirements:-
To run this project, install the following:

bash
Copy
Edit
pip install tensorflow matplotlib numpy
How to Run
Clone this repository:

bash
Copy
Edit
git clone :https://github.com/SUBIRSARKAR100/Machine-Learning-Course/blob/main/Assignment_1_digit_recognize%20(1).ipynb
Open the notebook in Google Colab or Jupyter Notebook.

Run all cells to train the model and test predictions.

###Output Example
Test Accuracy: Around 0.98 (98%).

Predicted digit for the first test image is displayed along with the actual digit.

Author
Your Name :- SUBIR SARKAR

Machine Learning Assignment 1

