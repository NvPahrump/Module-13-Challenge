# Module-13-Challenge

FinTech Bootcamp Module 13 Challange due June 18, 2023

# Challenge - Venture Funding with Deep Learning

Venture Funding with Deep Learning notebook

## Analysis

We use machine learning and neural networks to create a binary classifier model that will predict whether applicants can become successful.

The CSV file contains a variety of information about these businesses including past successes.

## Purpose

We provide risk management associate expertise at Alphabet Soup venture capital firm.

## Steps

### Prepare the Data for Use on a Neural Network Model 

### Compile and Evaluate a Binary Classification Model Using a Neural Network

### Optimize the Neural Network Models to improve Accuracy

### Save the models to HDF5 files

## Results

Original Model Results

	shape    parmeters	activation 
	
	 58       6786		relu
	 29       1711		relu
	  1         30 		sigmoid

	268/268 - 0s - loss: 0.5556 - accuracy: 0.7300 - 279ms/epoch - 1ms/step

Alternative Model 1 Results

	shape    parmeters	activation 
	
	117      13689		relu
	  1        118 		sigmoid

	268/268 - 0s - loss: 0.5733 - accuracy: 0.7292 - 252ms/epoch - 941us/step

Alternative Model 2 Results

	shape    parmeters	activation 
	
	117      13689		relu
	 58       6844		relu
	 30       1770		sigmoid
	  1         31 		sigmoid

	268/268 - 0s - loss: 0.5506 - accuracy: 0.7306 - 277ms/epoch - 1ms/step

## Summary

From the Original Model increase the loss by 0.0177, decrease the accuracy on Alternative Model 1 by 0.0008.

From the Original Model we were able increase the accuracy by 0.0006. 
decrease the loss on Alternative Mode 2 by 0.0050.

# github.com repository link

	https://github.com/NvPahrump/Module-13-Challenge

## Technologies

This app is designed for Python 3.7 notebooks on Anaconda 3

It uses Python 3.7 libraries

	numpy
	pandas
	pathlib
	matplotlib
	tensorflow
	sklearn
    
## Source Files:

    README.md

	venture_funding_with_deep_learning.ipynb

##  Resource Files:

#### Input data

	Resources/applicants_data.csv
    
#### Output files
    
	Resources/AlphabetSoup.h5
    Resources/AlphabetSoup_A1.h5
    Resources/AlphabetSoup_A2.h5

## To Run on Anaconda 3:

	jupyter lab &

	venture_funding_with_deep_learning.ipynb

## Contributors

Randy Miyazaki modified venture_funding_with_deep_learning.ipynb for the class assignment

## License

Intended for Randy Miyazaki and Fintech Bootcamp class personnel
