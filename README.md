# Circles-Classification-with-Neural-Networks
This project demonstrates binary classification on synthetically generated data using neural networks. The data consists of 1000 samples with 2 features (X_1, X_2) generated in a circular pattern using scikit-learn's make_circles function. The labels are balanced with 500 samples for each class (0 and 1). 

After visualizing the data, a simple 1 layer neural network model is built with Keras/Tensorflow and trained for 5 epochs. This initial model performs poorly at 50% accuracy. The model is improved by adding more layers, ReLU activations, and training for more epochs. The final model has 100-10-1 architecture with Sigmoid output and achieves 100% accuracy after 100 epochs. 

Model evaluation is done by plotting the decision boundary to visualize separation. Additional metrics include the confusion matrix to show true positives, true negatives, false positives and false negatives. As the classes are balanced and accuracy is 100%, the confusion matrix indicates no errors, so the model has not overfit on this simple dataset.

The training history is also plotted to analyze the loss curve. The loss decreases smoothly over epochs, further indicating the model has learned effectively.

In summary, this project shows an end-to-end workflow for binary classification on synthetic data using neural networks in Keras/Tensorflow. The techniques demonstrated include data visualization, model development, training loop, evaluation and plotting results.
