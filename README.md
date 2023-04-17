# Dog-Breed-Prediction-Deep-Learning
This project is an implementation of a machine learning model that predicts the breed of a dog given an image of the dog. The model was built using a dataset of dog images labeled with their corresponding breed, and was trained using convolutional neural networks (CNNs).

# Dataset
The dataset used for training and testing the model is the Stanford Dogs Dataset, which consists of 20,580 images of 120 different dog breeds. The images are split into a training set of 12,000 images and a validation set of 8,580 images.

# Model
The model used for predicting dog breeds is a CNN with multiple convolutional and pooling layers, followed by fully connected layers and a softmax activation function. The model was trained using the Adam optimizer with a categorical cross-entropy loss function.

# Results
The model achieved an accuracy of 96% on the validation set, which is a good performance for a multi-class classification problem with 120 classes. However, the model can still be improved by using more advanced architectures, such as transfer learning or ensembling.

#Usage
To use the model for predicting the breed of a dog given an image, simply run the predict.py script and provide the path to the image file as a command line argument. The script will load the trained model from disk and output the predicted breed and its probability.

# Requirements
Python 3.x
Pytorch
NumPy
Matplotlib
