# Numbers Identifier

This is a small project for recognition of hand-written numbers from *mnist* dataset. Here I use an artificial and convolutional neural networks and compare their accuracy. 

- First model has no hidden layers and shows ~93% of accuracy on test data
- The next one contains one hidden layer and shows ~97% of accuracy on test data
- CNN has 2 Conv2D, 1 hidden and an output layer with a different activation function and shows almost 99% of accuracy on test data

All models were trained during 5 epochs and compared through confusion matrix.
