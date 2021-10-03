#  AlexNet Inspired Architecture for CIFAR10 data
Author: Huygens Ravelomanana
# Description
We build an AlexNet inspired architecture for the CIFAR10 dataset from [https://www.cs.toronto.edu/~kriz/cifar.html](https://www.cs.toronto.edu/~kriz/cifar.html).<br>
We report the training history and evaluate the model on a test data .<br>
+ We first load the data and do some image preprocessing and data augmentation.
+ We then describe the AlexNet architecture and explain our approach.
+ We do some random grid search cross-validation to find the best hyperparameters for our model.
+ We build and train the model with the `"best"` hyperparameters we found.
+ Finally, we evaluate the model on test (unseen) data. We got 85% accuracy and 85%  f1-scores (both macro and weighted average) on the test data.
