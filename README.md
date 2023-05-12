# Machine-Learning

LAB1

Linear regression - makes predictions by plotting a straight line that approximately fits our data set.
It also makes the use of the cost function which will determine the error between the predicting value and the actual value.
This cost function which is the representation of the error to be minimum.
Gradient descent algorithm is used to find the minimum value of the cost function.

LAB2

Decision Tree - A decision tree is a type of supervised machine learning used to categorize or make predictions based on how a previous set of questions were answered. The model is a form of supervised learning, meaning that the model is trained and tested on a set of data that contains the desired categorization.

LAB3

3a
Neural Networks - The code uses TensorFlow and Keras libraries for building and training a neural network model.
It defines a sequential model with dense layers to process and classify data.
The model is trained using the MNIST dataset, which consists of images of handwritten digits along with their corresponding labels.
The pixel values of the images are normalized to a range between 0 and 1.
The model is compiled with an optimizer (Adam) and a loss function (SparseCategoricalCrossentropy).
It is then trained on the training data for a specified number of epochs.
After training, the model is evaluated on the test data to measure its accuracy.

3b
Image processing - The code uses TensorFlow and Keras libraries for building and training a neural network model.
It defines a sequential model with dense layers to process and classify data.
The model is trained using the MNIST dataset, which consists of images of handwritten digits along with their corresponding labels.
The pixel values of the images are normalized to a range between 0 and 1.
The model is compiled with an optimizer (Adam) and a loss function (SparseCategoricalCrossentropy).
It is then trained on the training data for a specified number of epochs.
After training, the model is evaluated on the test data to measure its accuracy.

LAB4

Clusterin using K-Means - The code utilizes scikit-learn library for K-means clustering.
It reads a dataset from a CSV file and visualizes the data points using a scatter plot.
Missing values in the dataset are filled with a placeholder value.
Features are scaled using MinMaxScaler to ensure their values lie within a specific range.
K-means clustering is applied to the scaled features to assign cluster labels to the data points.
Cluster centers and data points belonging to each cluster are plotted on a scatter plot, along with the sum of squared error for different values of K (number of clusters).
