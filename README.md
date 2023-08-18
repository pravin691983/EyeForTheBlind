# EYE FOR BLIND

> To create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset.

## Table of Contents

- [Problem Statement Business Objectives](#problem-statement-business-objectives)
- [Data in depth](#data-in-depth)
- [Approach](#approach)
- [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement Business Objectives

In this capstone project, you need to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library.

This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

### Want to

- To create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset.
- The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

## Data in depth

- We are going to analyze datasets,
- The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

## Approach

- The major steps that you have to perform can be briefly summarised in the following below steps:

#### Data Understanding:

- To gain insights from data we must look into each aspect of it very carefully. Here, you need to load the data and understand the representation.

#### Data Preprocessing:

- In this step, you will process both images and captions to the desired format.

#### Train-Test Split:

- Combine both images and captions to create the train and test dataset.

#### Model Building:

- This is the stage where you will create your image captioning model by building Encoder, Attention and Decoder model.

#### Model Evaluation:

- Evaluate the models using greedy search and BLEU score.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Python
- Numpy
- Panda
- Matplotlib
- Seaborn
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@pravin691983] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
