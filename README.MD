# Titanic Survivors

The RMS Titanic disaster was one of the most significant maritime tragedies of the 20th century, resulting in 1,517 deaths and 706 survivors out of 2,223 passengers.
This project aims to predict the survival of an individual on the Titanic based on various metrics 
and implementations of machine learning models and statistical techniques.

## The Problem

The initial dataset is publicly available but contains a substantial amount of missing data, making it difficult to identify patterns 
in the characteristics of individuals at first glance. Given this partially incomplete dataset, the goal was to create a logistic 
regression model to predict survival, identifying the most influential features that determined whether a person survived or not.

## Dataset Cleaning

As mentioned earlier, the dataset is incomplete, with many missing values. 
The solution involved using statistical methods to impute missing data or filling in the gaps based on visualizations and 
evidence of the importance of specific variables in determining survival. Some variables that were not useful or significant 
were justifiably excluded from the dataset or not used during training.

## Technologies
- Python
- TensorFlow
- Jupyter Notebook
- NumPy, Pandas, Matplotlib, Scikit-learn

## The Solution

The solution was to implement a logistic regression machine learning model. 
This model was chosen because the project's scope did not require a heavy solution like a neural network, 
as it involves binary classification. After building the model, it achieved an accuracy of 77% using RMSProp optimization. 
The model was saved in `.h5` format for later deployment on a web page, where it can be tested freely (currently under development).

You can view the project's progress documented in each Jupyter Notebook, from dataset cleaning to model creation.
