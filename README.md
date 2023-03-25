# ML-via-Python
In this code, we first import the necessary libraries, including TensorFlow and Keras for the machine learning components, and Matplotlib for visualization. We then load the CIFAR-10 dataset using the datasets.cifar10.load_data() function, which returns separate sets of training and testing images and labels.

Next, we normalize the pixel values of the images to be between 0 and 1 using simple division. We then define the architecture of our CNN using the Sequential class from Keras. This includes multiple convolutional layers, max pooling layers, and dense layers with activation functions like relu and softmax.

We then compile the model using the compile method, which specifies the optimizer, loss function, and metrics to track during training. We then train the model using the fit method, which takes in the training data and labels, as well as the number of epochs to run.

After training, we evaluate the accuracy of the model on the test data using the evaluate method. Finally, we plot the training and validation accuracy over time using Matplotlib.
