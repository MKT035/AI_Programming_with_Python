# AI Programming with Python Nanodegree
This repository contains the submissions for the nanodegree program [AI Programming with Python](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089) offered by [Udacity](https://www.udacity.com/).

The foundation of the code was provided by Udacity as a starting point for the projects.

## Pre-trained Image Classifier to Identify Dog Breeds

The first project dealt with using a given image classifier in order to identify dog breeds. The focus was not on training or building the classifier, but on demonstrating the necessary Python skills for setting up a machine learning project, i.e. dealing with the data, looking at different metrics, inspecting results and run times of different classifiers.


## Own Image Classifier to predict Flowers

### Training
1. Checkout this repository and navigate into `image_classifier_flowers/ImageClassifier`
2. Run `python train.py <data_directory>` (the script is written in such a way that the user is informed about all the steps taken (building the network, training, ...))
3. To see all the possible customizations, run `python train.py --h`

### Predicting
1. Checkout this repository and navigate into `image_classifier_flowers/ImageClassifier`
2. Run `python predict.py <path_to_image> <checkpoint>` (note that a valid checkpoint needs to be given)
3. To see all the possible customizations, run `python predict.py --h`