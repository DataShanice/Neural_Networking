# Neural Networking Challenge 19 
## Objectives 
The goals of this challenge is to:

Import, analyze, clean, and preprocess a “real-world” classification dataset.
Select, design, and train a binary classification model of your choosing.
Optimize model training and input data to achieve desired model performance.

## Instructions 
Create a new Jupyter Notebook within a new folder on your computer. 
Name this new notebook file “AlphabetSoupChallenge.ipynb” (or something easily identifiable).

Download the Alphabet Soup Charity dataset (charity_data.csv)Preview the documentand place it in the same directory as your notebook.
Import and characterize the input data

Using the methods described in this module, preprocess all numerical and categorical variables, as needed:
Combine rare categorical values via bucketing.

Encode categorical variables using one-hot encoding.
Standardize numerical variables using Scikit-Learn’s StandardScaler class.

Using a TensorFlow neural network design of your choice, create a binary classification model that can predict if an Alphabet Soup funded organization will be successful based on the features in the dataset.


Compile, train, and evaluate your binary classification model. Be sure that your notebook produces the following outputs:
Final model loss metric
Final model predictive accuracy

Do your best to optimize your model training and input data to achieve a target predictive accuracy higher than 75%.

## Summary

For the Nueral Network Model, within Layer 1 I selected 8 nuerons, however, for Layer 2 I ran 5. In order to improve accuracy from a very low 0.533, I figured changing the number of layers could possibly improve its accuaracy. Unfortunately that was not the case for this model. I was able to identify the issues with working wioth a Deep Neural Network as opposed to a Single Layer Network. The Single Layer Network proved to be much more accurate at 0.722. This finding can conclude that while having additional layers can be beneficial, in this case, it did not improve the performance. 

