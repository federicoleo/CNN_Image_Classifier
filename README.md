# 🐶 End-to-end Multi-class Dog Breed Classification
<a target="_blank" href="https://colab.research.google.com/drive/1xrqAj120BRl5b8OWtP1Fu9Z4_o_e6bF7#scrollTo=LTpB_uSLXeKV">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This notebook builds an end-to-end multi-class image classififer using TensorFlow 2.0 and TensorflowHub.

## 1. Problem

Identifying the breed of a dog given an image of a dog.

When i'm sitting at a cafe and i'm taking a photo of a dog I wanna know which breed the dog is.

## 2. Data

Data from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

## 3. Evaluation

The evaluation is a file with prediction prob for each dog breed of each test image.

Multi Class Log loss.

## 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so it's probably best we use deep learning / transfer learning.
* 120 breeds of dogs, 120 different classes.
* 10,000+ images in the training set. (these have labels.)
* 10,000+ images in the test set (these have no labels, we want to predict them.)
