# iris
Machine learning demo with sklearn using K Nearest Classifier. See 'iris - Jupyter Notebook.pdf' for output.

This demo uses the Iris dataset from Sci-kit learn which consists of 3 different types of Iris flower: setosa, versicolor and virginica.

Each flower has the following characteristics:

- sepal length
-  sepal width
-  petal length
-  petal width

The dataset is configured as a Numpy array and then split 4:1 into training data and test data.

A K Neighbours classifier model is created using sklearn and the model is fitted to the training data. 

The model is then tested against the test data. Sklearn indicates an accuracy of 93%. A different model is tried (decision classifier) but this does not improve the accuracy.

The model is saved and plots created using Matplotlib.
