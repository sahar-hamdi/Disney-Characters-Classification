# Disney-Characters-Classification
Classification of Disney Characters using CNN 

Dataset: https://www.kaggle.com/datasets/sayehkargari/disney-characters-dataset

# Introduction# 

This repository contains the code and analysis for the Disney Characters Dataset Analysis and Classification using CNN project. 


# Dependencies#
Python 

Jupyter Notebook (to run the .ipynb notebook)

** Libraries**:
    * Pandas
    * NumPy
    * Matplotlib
    * Pytorch
    * math


# Usage :#

    Open the Jupyter Notebook (https://github.com/sahar-hamdi/Disney-Characters-Classification/blob/main/classification-of-disney-characters.ipynb) to access the code and analysis. The notebook contains step-by-step explanations and code to perform the following tasks:

    * Data loading and exploration
    * Data visualization and analysis
    * Data preprocessing and feature engineering
    * Model training and evaluation using CNN 

    Simply run the notebook cells to follow along with the analysis and classification process.

    

# Methods:#
    The following methods are implemented in this project:
         * CNN Layers 
         * Linear Layers
         * Forward Pass
        The first convolutional layer takes input with 3 channels (typical for RGB images) and outputs 4 feature maps. It uses a 3x3 kernel, padding of 1, and a stride of 1.
    - Batch normalization is applied to normalize the output of each convolutional layer, which helps with training stability.
    - ReLU activation functions introduce non-linearity.
    - Max-pooling with a 2x2 kernel reduces the spatial dimensions of the feature maps.
    - After the convolutional layers, the feature maps are flattened.
      Then, the flattened features are passed through the linear_layers to produce the final output.

# Results:#
  Print the number of trained images and the Accuracy of the model, then tested the model to predict names of Some Dataset Characters 
  
  and the model predicted it Correctly.
