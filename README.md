<a href="https://colab.research.google.com/github/Madhur6234/Multi-class-Dog-Breed-Classification/blob/main/dog_breed_identification.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# 🐶 Multi-class Dog Breed Classification

### [Google Colaboratory Link](https://colab.research.google.com/github/Madhur6234/Multi-class-Dog-Breed-Classification/blob/main/dog_breed_identification.ipynb) | [Jupyter Notebook - NBViewer Link](https://nbviewer.jupyter.org/github/Madhur6234/Multi-class-Dog-Breed-Classification/blob/main/dog_breed_identification.ipynb)

This project builds an end-to-end multi-class image classifier using **TensorFlow 2.0** and **TensorFlow Hub** which helps us identify different breeds of dogs.

To do this, we'll be using data from the **[Kaggle dog breed identification competition](https://www.kaggle.com/c/dog-breed-identification/overview)**. It consists of a collection of 10,000+ labelled images of 120 different dog breeds.

This kind of problem is called multi-class image classification. It's multi-class because we're trying to classify multiple different breeds of dog. If we were only trying to classify dogs versus cats, it would be called binary classification (one thing versus another).

#### Libraries used:
    * NumPy
    * Pandas
    * Matplotlib
    * TensorFlow
    * TensorFlow Hub
    * IPython
    * Scikit-learn (sklearn)

## Some important points about the project:

### 1. Problem

Identifying the breed of a dog given the image of a dog.

### 2. Data

The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

### 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

### 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set (these images have labels).
* There are around 10,000+ images in the test set (these images have no labels because we'll want to predict them).
