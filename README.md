# Autoencoder-of-mnist-dataset
This is the python code for developing autoencoder using mnist dataset


Here first we Normalize mnist dataset in the range [0, 1]. 
And the number of features in a dataset be N. Then train an autoencoder with two hidden layers for each dataset. 
The input, first hidden layer, second hidden layer, and the out layer has N, N/2, N/4, and N nodes, respectively. 
The input layer has linear nodes, the hidden layers have leaky ReLU nodes. The output layer has sigmoidal nodes. 
Then we are Extract the features from the second hidden layers. 
And atlast Perform c-means clustering on the extracted feature space.
