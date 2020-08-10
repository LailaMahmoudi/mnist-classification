# MNIST digit classification in python using scikit-learn- Stochastique gradient descent and random forest

 ## Table of contents


 ## Summary

 ## Import the relevant libraries

 ## Loading the MNIST data

 ## Exploratory data analysis
 

 ## Preprocess the data set
   ### Cleaning the data set
 
   ### Separate Features and Labels
   
    
 ## Plotting the data set
 

 ## Data Splitting Process
 

 ## Training Process

   ### Training a binary classifier
    
  ###### STOCHASTIQUE GRADIENT DESCENT
  ###### RANDOM FOREST ALGORITHM

    
 ## Performance Measures

   ##### Cross Validation
   ##### Confusion Matrix
   ##### Precision 
   ##### Recall 
   ##### F1 
   ##### Precision/Recall Trade-off
     
        
 ## The Test set
 
 
 
 
 
 
 
# SUMMARY
  
The goal of this notebook is to analyze a classification model with the MNIST data, so in this notebook, i will detect one number from MNIST data set using binary classifiers (A  classifier is an algorithm of machine learning that will determine the class to which the input data belongs to, based on a set of features). And then i will evaluate the measures of performance, and choose the model that have a great accuracy.

In This notebook, i will use the most popular machine learning approches to solve this classification problem by using the sklearn library.



# The Data set

In this notebook I am using the MNIST Digits dataset is an open dataset and is available in Kaggle which can be accessed from the link below.

[\](https://www.kaggle.com/c/digit-recognizer)


The dataset consists of 10 classes of handwritten Images pictures each with a number between 0-9,  and each image has 784 features, this is beacuse each image is 28*28 pixels.





# Project Setup




## Installation

A very easy way to install these packages is to download and install the Conda distribution. This distribution of conda is available on all platforms (Windows, Linux and Mac OSX).




## Dependencies

The main libraries involved in this notebook are:

-NumPy  :  for multidimensional array computing

-Pandas :  for data manipulation

-SciKit-Learn : for machine learning Techniques

-Matplotlib   : for data visualization



## Key Concepts


Workflow steps:
    
   
  - Acquire the dataset
  - Explore the dataset
  - Preprocess the dataset
  - Visualize the dataset
  - Split the data 
  - Model training
  - Measure the performance 
  - Submit the results


# How the project is organized

The Project consist of four files:
    
   - Explore and Preprocess the data set.ipynb
   
   - Visualizing, Spliting the data set and Training the model .ipynb
   
   - Model Evaluation.ipynb
   
   - Submit the results.ipynb
