# Iris Data Set - Keras Neural Network

## Emerging Technologies - Problem Sheet 4

This respository contains solutions to a set of problems concerning neural networks using Tensorflow. For the purpose of
this example we apply the *Iris* data set previously used in another problem set you can you find
[HERE!](https://github.com/damiannolan/iris-data-set)

Previously, in the repository linked above we looked at loading the *Iris* csv data with Python and inspecting it using
[Matplotlib's Pyplot](https://matplotlib.org/users/pyplot_tutorial.html). We then investigated how to determine the best
fit line for the data set and various subsets using [Numpy's
polyfit](https://docs.scipy.org/doc/numpy-1.13.0/reference/generated/numpy.polyfit.html) and by also writing our own gradient descent algorithm. We took a brief look a Scatterplot matrices using a relatively new library called [Seaborn](https://seaborn.pydata.org/).

## Problem Set

In this Problem Set we look at the following issues:

- Preparing the data
- Splitting data in two subsets: Training and Testing
- Creating a Neural Network Model
- Training the Model using the Training data subset
- Evalutation of the Model's accuarcy using the Testing data subset
- Prediction of class specification of Iris Flower species using the Model

All of the Python code relating to the Problem Set can be found in the juptyer notebook housed in this repository, which also contains a wide range of Markdown notes documenting and describing the tasks being carried out.

## The Iris Data Set

The data set contains samples of 3 different types of *Iris* plant.

- Setosa
- Versicolor
- Virginica

The data samples contain 50 samples for each of the different types of species. Each sample is composed of 4 distinct
features of the plants including:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Usage & Dependencies

Should you want to clone this repository and adapt the code for yourself, you will need the following prerequisites that
you can obtain via the *pip* package manager.

1. Clone the repository
```
git clone https://github.com/damiannolan/iris-neural-network.git
```

2. Start Jupyter Notebook
```
jupyter notebook
```

If you are new to Python you may want to follow to the instructions below for installing a number of different
dependencies.

### Python
You can download for Windows by following instructions [here!](https://docs.python.org/3/using/windows.html). If you are
on MacOS I recommend using [Homebrew](https://brew.sh/)

```
brew install python3
```

Alternatively you can download a larger distribution which will include a number of different packages from
[Anaconda](https://anaconda.org/anaconda/python).

### Numpy
You can obtain Numpy, SciPy and Matplotlib with:

```
brew tap homebrew/science && brew install python numpy scipy matplotlib
```

### Jupyter Notebook

```
pip3 install jupyter
```

### Tensorflow

```
pip3 install tensorflow
```

### Keras

```
pip3 install keras
```

