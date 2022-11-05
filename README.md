# 🐶 End to End Multi class Dog Breed Identification
- Source - https://www.kaggle.com/competitions/dog-breed-identification/overview


## 1. Problem 
Identifing the breed of a dog given an image of a dog.

## 2. Data 
from kaggle,
data :- https://www.kaggle.com/competitions/dog-breed-identification/data

## 3. Evaluation
The evaluation is a file with prediction probabilities for each dod breed of each test image 
https://www.kaggle.com/competitions/dog-breed-identification/overview/evaluation


## 4. Fautures 
Some information about the data:
* We are dealing with images (unstructured data ) so it's probably best we use deep learning/transfer learning.
* There  are 120 breeds of dogs (this means there are 120 differnt cases).
* There are more than 10,000+ images in training set
* There are around 10,000+ images in the test set (these images have no labels, because, it will be predicted)


# Workspace 
* TensorFlow 2.x
* TensorFlow Hub
* Using GPU 

## Model from Tensorflow Hub
* MODEL_URL = 'https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/5'
