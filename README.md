# Food-Vision-Project

This Project gives the name of the Food item from the picture we give it as input. (Only from 101 options) 

## Dataset 

- We will get the data from Tensorflow Datasets (TFDS)

What is TensorFlow Datasets?
- A place for prepared and ready-to-use machine learning datasets.

Why use TensorFlow Datasets?
- Load data already in Tensors
- Practice on well established datasets
- Experiment with differet data loading techniques (like we're going to use in this notebook)
- Experiment with new TensorFlow features quickly (such as mixed precision training)

Why not use TensorFlow Datasets?
- The datasets are static (they don't change, like your real-world datasets would)
- Might not be suited for your particular problem (but great for experimenting)

Dataset we are going to use -> 
https://www.tensorflow.org/datasets/catalog/food101

## Modelling

- We will be using Transfer Learning technique(EfficientNetB0). 
- We will build 2 Models 
  1. Feature Extraction Model
  2. Fine Tuning Model 

## Accuracy 

Our Goal is to beat [DeepFood](https://www.researchgate.net/publication/304163308_DeepFood_Deep_Learning-Based_Food_Image_Recognition_for_Computer-Aided_Dietary_Assessment), a 2016 paper which used a Convolutional Neural Network trained for 2-3 days to achieve 77.4% top-1 accuracy.
