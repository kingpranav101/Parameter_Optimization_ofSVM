# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope](https://archive.ics.uci.edu/ml/machine-learning-databases/magic/)

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 19020

Number of Attributes: 11

## Final Result Table

Sample	Best Accuracy	Best Kernel	Best Nu	Best Epsilon
0	1	0.62	rbf	0.62	0.07
1	2	0.71	rbf	0.36	0.69
2	3	0.64	rbf	0.48	0.25
3	4	0.71	rbf	0.21	0.92
4	5	0.72	rbf	0.22	0.75
5	6	0.73	rbf	0.40	0.52
6	7	0.62	rbf	0.86	0.12
7	8	0.71	rbf	1.00	0.91
8	9	0.41	rbf	0.97	0.33
9	10	0.72	rbf	0.30	
## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample  has the best accuracy of 0.62 having kernel = Poly, Nu = 0.86 and Epsilon = 0.12.

## Written By
Name : Pranav
  
Roll No. : 102053019

Sub-Group: 3CO17