# Devanagari Handwritten Character Recognition

The dataset used for this project can be downloaded from https://archive.ics.uci.edu/ml/machine-learning-databases/00389/DevanagariHandwrittenCharacterDataset.zip

This project implements a Machine Learning model using Logistic Regression algorithm to train and test against the Devanagari Handwritten Character Dataset.

This project also build Neural Networks to train and test.

### **Requirements**
   - Python3
   - Logistic Regression
   - Deep Neural Network
   - Convolution Neural Network
   - Keras

The neurals networks build for character recognition are -
- **DEEP NEURAL NETWORK**

  The DNN consists of 3 layers that are input layer, hidden layer and output layer.
  
  The input layer expects an array of shape (1024,), corresponding to the flattened pixel values of a single 32x32 grayscale image. 
  The hidden layer is fully connected layer with 1024 neurons and ReLU activation function and the output layer 
  with 46 neurons (one for each class) and softmax activation function to generate the probability distribution over the output classes.
  
 - **CONVOLUTION NEURAL NETWORK**
 
    The CNN consists of input layer, two 2D convolutional layer, flatten layer and the output layer.
    
    For both the 2D convolutional layers ReLU (Rectified Linear Unit) activation function is used. The Dense layer is 
    fully connected layer with 46 units (neurons) and the activation function used is "softmax".
