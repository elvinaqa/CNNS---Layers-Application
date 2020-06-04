# CNNS---Layers-Application
Convolutional Neural Networks implementation and application

# Kernels Example in setosa io

Notes:
 Parameters which should be changed according to the statement of the problem:
 input_shape in the Convolutional Layer, which should be as the shape of the one element in the train/test set# number of neurons in the Dense layer which is final output layer - 10 in this specific problem where there are 10 classes
 activation function in the final Dense layer which is SOFTMAX, for multi-class classification problem# activation fucntion could be SIGMOID for binary classification problem, such as Dog, or Cat Images problem
These kernels - filters are 
# Convolutional Kernels

![Screenshot (177)](https://user-images.githubusercontent.com/57037068/83547008-a4236980-a512-11ea-8fb2-524a166fa258.png)

# Difference between ANN vs CNN, etc
![LgmYv](https://user-images.githubusercontent.com/57037068/83766789-e329fa00-a68d-11ea-9dff-5dbb924ba64b.png)

# ANN - Fully Connected, thus, lots of parameters to deal with
![Ann](https://user-images.githubusercontent.com/57037068/83767215-6cd9c780-a68e-11ea-9956-40610c784f7b.PNG)

# CNN - Only Localized connectivity, less parameters (filters can be added after each layer & weights can be calculated)
![conv](https://user-images.githubusercontent.com/57037068/83767224-706d4e80-a68e-11ea-8d94-85dfc67334bc.PNG)

# Pooling layers remove some less important parts of the input data (convolutional layer) while preserving the main skeleton parts 
Even a small layer can remove 75% of the input data by a 2x2 kernel and 2 strides
![pooling](https://user-images.githubusercontent.com/57037068/83769388-d4911200-a690-11ea-8bf3-9ab4b61ba71c.PNG)
