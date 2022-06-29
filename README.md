# Algorithms and methods of artificial intelligence Cracow University of Technology Bootcamp.

## Project I 
### Regression - full ML pipeline - Boston Housing

- Exploratory analysis - summaries, some visualizations, error identification, etc.
- Model selection and training
- Model testing + visualisation of performance (e.g. plotting a straight line for a selected variable with a linear model)

## Project II
### Implementing a classifier using the bagging method together with hard voting (but without using the class provided by scikit-learn!)

- Implementing a function that will generate bootstrap samples from a given dataset
- The function can additionally determine OOB data, i.e. those not used for training (e.g. by set difference or negation of indexing - pandas supports such miracles)
- Code that will add models (these can already come from scikit-learna) to some list
- Iterate through this list and train each model (each model is to be trained with a different bootstrap)
- Next function - testing. You can use the OOB data from point 1a or use a dedicated learning set 
- Last function - performing hard voting - again iterating over all models, generating a prediction and calculating the mod

## Project III
###  Classifier based on a fully connected network

- IMDB dataset classification

## Project IV
### Convolutional Neural Network

- The task is to create a convolutional network that allows to recognise clothes on the basis of the MNIST Fashion set.
- Please visualise several convolutional filters (what the network "sees") - this involves passing a sample through the network (forward pass), taking the activation value of the selected layer and filter, and then displaying it via imshow.
- Additionally, please apply the Softmax layer and for several examples display a bar chart (barplot) with probabilities, predicted value and true value - please also include the checked image on the chart (with matplotlib).
- The project should include training and testing of the network.
