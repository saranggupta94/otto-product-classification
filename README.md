# otto-product-classification

### Project Overview

This project aims to train a machine learning algorithm that is able to classify a product into
different categories based on the product characteristics. The project is based on Kaggle
competition - Otto Group Product Classification Challenge. The data set provided by the
Otto group consists of product features and their categories for around 60,000 products. This
project aims to use the labelled data and supervised learning techniques to develop an
algorithm for predicting the product categories given the product features.

### Solution Overview

With the given problem statement and dataset, the project will use supervised probabilistic
classification algorithms to classify the products into different categories. The given dataset
will be split into training and testing sets. Supervised learning will be used to train the
algorithms to predict the probability distribution of the product belonging to the different
categories given its input features. The proposed solution will use an ensemble of
classification algorithms. The developed model will be evaluated on the test set using log-loss
function which is discussed in the Evaluation Metrics section.
The project will be approached in 4 stages –
1. Data Exploration and Pre-Processing
The first step of the project would be to analyse and pre-process the dataset. Dataset will be
cleaned to remove unwanted values (such as product ids) and encode the target labels.
Feature scaling and normalizing techniques will be used to scale skewed features.
2. Dimensionality Reduction
The given dataset consists of 93 features. This is a large feature set and this section will
explore dimensionality reduction and feature selection for reducing the input feature set.
Principal component analysis will be used to explore the viability of dimensionality reduction
for the dataset.
3. Supervised Learning
Next step would to use the reduced feature set and target labels to train supervised
classification models. Different classification algorithms that will be explored are - random
forests, K-Nearest Neighbours and boosting. These algorithms have been chosen as potential
candidates because of their ability to work with multiclass classification problems and output
a probability distribution over target classes. In addition to looking at the individual
algorithms’ performance, ensemble learning approach will also be explored.
4. Model Testing
The trained models will be evaluated on the test data set using the log loss function defined in
the Evaluation Metrics section. Models’ performance on both test and training dataset will be
evaluated for signs of overfitting. The goal of the training process would be to minimize the
log loss function on the test data set.

### Development Environment:
-Python 3.x
-Sklearn 0.17
-Pandas
-Numpy
-Matplotlib

### Dataset
- The input dataset can be found in the folder: input\dataset.csv

### Models
- The models folder is empty. While running the notebook, the models will be pickled and stored in this folder.
