# COVID-19-Autoencoder
Using Autoencoder in keras as a nonlinear dimensionality reduction method.The goal is to reduce and encode patients data in a 2d space which could be seperated easily.
## Data Documnetation

We used Symptoms and COVID Presence (May 2020 data) dataset.COVID is a contagious disease. The purpose of this dataset is to provide symptoms as input and it should be able to predict if COVID is possibly present or not. It cannot be used for serious medical purposes.
For more information please read the [data documentation](https://www.kaggle.com/datasets/hemanthhari/symptoms-and-covid-presence).

## Code Explanation
- **0. Preparation**: A section that loads the dataset using pandas, encodes the categorical features using LabelEncoder, and splits the data into train and test sets.
- **1. DNN as nonlinear dimensionality reduction method**: A section that defines and trains an autoencoder using Keras, which compresses the data from 20 dimensions to 2 dimensions and then reconstructs the original data. The section also plots the encoded data using matplotlib.

![result](/output.png)
