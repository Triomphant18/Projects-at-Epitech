# Project: Fashion-MNIST Classification

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

### Ensemble Methods

1. Create a BaggingClassifier model from scikit-learn, combining the KNeighborsClassifier, OneVsRestClassifier, and DecisionTreeClassifier. This ensemble model uses multiple machine learning algorithms to improve predictive performance.
2. Display the performance indicators of your ensemble model, including the precision score, recall score, and confusion matrix.
3. Try different combinations and hyperparameters for the ensemble model. Identify the best combination that provides the highest performance.

### Random Forest Classifier

1. Create a RandomForestClassifier model from scikit-learn.
2. Display the performance indicators of your Random Forest model, including the precision score, recall score, and confusion matrix.
3. Try different numbers of trees in the forest. Identify the number of trees that results in the best performance.

## Author

Triomphant Ben Ali SUANON

## Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [BaggingClassifier Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingClassifier.html)
- [RandomForestClassifier Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
