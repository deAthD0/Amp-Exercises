# Week 2
Install scipy and sklearn on your system using 
```
pip install scipy, sklearn
```
## Regularization
Take a moment to go through the data in 'ex2data2.txt' as that is the data we'll be using for the regularization problem.
Here the data is shown of whether a microchip is of quality or not.
The first column contains the results of tests it underwent for test 1.
The second column contains the results of tests it underwent for test 2.
The third column shows whether it was selected or rejected.

The components for the exercise is given below:

* __regularizationmain.py__
The main file for the program, which will be using other files to  run the program.
An important difference is the use of feature mapping to increase the number of features. This is done to generate more features from existing ones, since the data we're fitting is non linear hence a line will never be able to fit it.
To enable this, we include the features and their polynomials raised to the sixth power as features too.

* __costFunctionReg.py__
The file contains the cost function that needs to be completed by you, keep in mind to use the regularization forumla.
The gradient function has already been completed for your ease.

# Sklearn implementation
The Sklearn libary is a boon to the community of machine learning, as it tremendously simplify the amount of code we have to write to achieve an accurate model. 
* __sklearn_log.py__
Contains the sklearn implementation of the Logistic regression problem we've implemented. Please go through it as it'll show you how our vast and multi file program reduces to merely 20 lines of code. Sklearn by default takes care of a lot of things for us, but allows us to customise functions as per our need. 
Read the documentation about sklearn and try implemting our previous exercises using sklearn

## Support Vector Machines

We'll be using Support Vecrtor machines to create a mini project of sorts. We'll be working on improving this project later on as well.
There are total four components in the file

* Main.py
 The main file for the program, here you will be loading in the SVM from sklearn and then train and store the model in a different file, which can be accessed by other files.
 You need to finish the SVM code in here
 
 * Detector.py
 The file will load in our image to test it on, and the classifier model, and predict the values.
 
 * photo8.jpg
 The sample File I'll be using to test the work. Once you've determined the model is working, you can swap it out for your own files to test it on.
 
 * digits_cls.pkl 
 The file you'll be generating by running Main.py to save the classifier, and the file Detector.py will  read to load in the classifier.

## Optional Exercise
Right now you're loading in data from one file, if you've gone through the openCV documentation,try and take the input from a livestream input via the webcam

# Kmeans using Sklearn implemntation
I have implemented an example of kmeans algorithm , clustering customers based on their loyalty and satisfaction. 
I have implemented the elbow method, using kmeans inertia to determine the best number of clusters. You can read more about them [here](https://analyticsindiamag.com/beginners-guide-to-k-means-clustering/). There's an exercise towards the end of the file, and I hope you'll implement it :3
