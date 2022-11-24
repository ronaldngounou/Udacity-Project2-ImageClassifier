# Udacity-Project2-ImageClassifier
Train an image classifier to recognize different species of flowers, then export it for use in a stand alone application.

## Overview
In this project, I will train an image classifier to recognize different species of flowers, then export it for use in a stand alone application.
This project was completed as part of Udacity's [AI Programming with Python Nanodegree](/https://www.udacity.com/course/ai-programming-python-nanodegree--nd089?utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=12949497746_c_individuals&utm_term=130336583708&utm_keyword=%2Bnanodegree%20%2Bpython%20%2Bai_b&gclid=CjwKCAiAyfybBhBKEiwAgtB7fl8mGnollqsIAzZLMhV1pMoopbYcaqvkK5ivRsTLajINWVHjGCId_xoCs0oQAvD_BwE) certification.

## Objectives
Implement an image classifier with PyTorch (build and train a neural network on the flower dataset).
Convert the classifier into an application that others can use. The application should be a pair of Python scripts that run from the command line. The first file, ``train.py``, will train a new network on a dataset and save the model as a checkpoint. The second file, ``predict.py``, uses a trained network to predict the class for an input image.

## Data Origin
The [102 Category Flower Dataset](/https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) consisting of 102 flower categories. The flowers chosen to be flower commonly occuring in the United Kingdom. Each class consists of between 40 and 258 images. The details of the categories and the number of images for each class can be found on this [category statistics page](/https://www.robots.ox.ac.uk/~vgg/data/flowers/102/categories.html) .

The images have large scale, pose and light variations. In addition, there are categories that have large variations within the category and several very similar categories. The dataset is visualized using isomap with shape and colour features.

## Tools, Software and Libraries
* Python 3.6
* torch, torchvision
* numpy
* json
* time
* os
* random
* matplotlib
* PIL
* argparse

## Results
A Python application that can be trained with PyTorch (using tranfer learning technique on a pre-train neural network) on any set of labeled images. The project is broken down into multiple steps:

* Load and preprocess the image dataset,
* Train the image classifier on your dataset,
* Use the trained classifier to predict image content.
