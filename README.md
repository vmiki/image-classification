# Udacity Deep Laerning Foundations Nanodegree

## Project 2: Image classification

In this project, I will classify images of the set [CIFAR-10 link](https://www.cs.toronto.edu/~kriz/cifar.html). This set contains images of airplanes, dogs, cats and other objects. The data needs to be preprocessed, then a convolutional neural network must be trained. It is necessary to normalize the images, make the one-hot encoding of the labels, and assemble the convolutional layers, max pooling and fully connected . At the end, the classifications proposed by the neural network for the images will be presented.

## Running using conda!

Run this in command line

**Step 1:** Create a new environment

```terminal
conda create --name image-classification python=3
```

**Step 2:** Use the new env

```terminal
source activate image-classification
```

**Step 3:** Install dependencies

```terminal
conda install -c conda-forge tensorflow=1.0.0
conda install -c conda-forge tqdm=4.11.2
conda install matplotlib scikit-learn jupyter notebook
```

**Step 4:** Open the notebook to run it

```terminal
jupyter notebook dlnd_image_classification.ipynb
```

## Project structure

This folder contains files for Udacity Deep Laerning Foundations Nanodegree Project 2: Image Classification.

**dlnd_image_classification.ipynb** - Main project file.

**dlnd_image_classification.html** - Neural network prediction results file.

**problem_unittests.py** - Unit tests provided by Udacity.

**helper.py** - Help functions provided by Udacity.