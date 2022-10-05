# real-or-fake-face-image-classification
A Logistic Regression algorithm implemented from scratch. We extracted spectral features by applying Discrete Fourier Transform.

Logistic regression with gradient descent, based on a data set of 500 real (labelled as '0') and 500 fake (labelled as '1') images.
After calculating the spectral features of each image and turning the images to data we can work with, we run the algorithm with predefined parameters for gradient descent.
We tested different values for each parameter to find the optimal set of parameters, taking into consideration both runtime and accuracy of the model. You can see some graphs in the notebook, comparing some of the parameters against each other.

The algorithm can then be used to classify new data, found in the "FutureData" folder, in the "TestData" folder. The results will be written to "FutureDataEstimatedLabels" csv file. You can see the results of the algorithm, ran on the test images, which were provided by the lecturer.
