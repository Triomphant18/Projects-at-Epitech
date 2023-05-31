# Project: Fashion-MNIST Classification using Dense Neural Network

Fashion-MNIST is a dataset of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image associated with a label from 10 classes. The value of each pixel is an integer between 0 and 255. Each training and test example is assigned to one of the following labels:

- 0: T-shirt/top
- 1: Trouser
- 2: Pullover
- 3: Dress
- 4: Coat
- 5: Sandal
- 6: Shirt
- 7: Sneaker
- 8: Bag
- 9: Ankle boot

## Objectives

The main objectives of this project are as follows:

1. Create a Dense model using Keras with the following layers:
   - An input layer of 784 neurons (pixels of the image).
   - A layer to rescale the input from the [0, 255] range to the [0, 1] range.
   - Two hidden layers of 64 neurons each, using the ReLU activation function.
   - An output layer of 10 neurons using the softmax activation function.
2. Compile the model with the following configurations:
   - Categorical cross-entropy as the loss function.
   - Adam optimizer with a learning rate of 0.001.
3. Fit the model to the training data for 30 epochs.
4. Display the performance indicators of your model, including the precision score, recall score, and confusion matrix.
5. Experiment with different numbers of hidden layers, different numbers of neurons, and different numbers of epochs. Identify the configurations that provide the best performance.

## Author

Triomphant Ben Ali SUANON

## Resources

- [Keras Documentation](https://keras.io/)
