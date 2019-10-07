# Cat-classifier
This is an application of the Logistic Regression with  a Neural Network mindset, it recognizes cat with 70% accuracy.
1 - Packages used 

numpy is the fundamental package for scientific computing with Python.
h5py is a common package to interact with a dataset that is stored on an H5 file.
matplotlib is a famous library to plot graphs in Python.
PIL and scipy are used here to test the model with your own picture at the end.

2 - We are given a dataset ("data.h5") containing:

- a training set of m_train images labeled as cat (y=1) or non-cat (y=0)
- a test set of m_test images labeled as cat or non-cat
- each image is of shape (num_px, num_px, 3) where 3 is for the 3 channels (RGB). Thus, each image is square (height = num_px) and (width = num_px).
I'm going to build a simple image-recognition algorithm that can correctly classify pictures as cat or non-cat.


3 - General Architecture of the learning algorithm
It's time to design a simple algorithm to distinguish cat images from non-cat images.

Im gonna build a Logistic Regression, using a Neural Network mindset. The following Figure explains why Logistic Regression is actually a very simple Neural Network!
<img width="518" alt="LogReg_kiank" src="https://user-images.githubusercontent.com/35849581/66330952-bb816700-e931-11e9-857f-4ad9fdeb6942.png">
