# CNN-Breast-Cancer-Diagnosis

This project tries to solve a real world problem of detecting and classifying early stage breast cancer. Breast cancer is one of the most common cancer and its early detection can help us save thousands of lives annually. 1 in 8 women in the US alone are expected to experience breast cancer in her lifetime (Source: https://www.breastcancer.org/symptoms/understand_bc/statistics), which makes this problem big enough to be considered as a suitable application for a machine learning solution.

## Key Challange

The key challange of the problem is how to classify a tumor into malignant or benign.

## Problem solving approach

In order to apply machine learning solution to any problem, we first need to understand the steps in which a perticular problem is solved and determine what steps might benifit from our machine learning algorithm. 

Not all problems can be conveniently solved using machine learning, and for critical applications like breast cancer classification, we have to make sure that our solution is good enough. One of the main problems which may hamper our use of ML solution is the availability of limited amount of data, which can cripple our output by overfitting our data to the training data. A good option to proceed in that scenario is the use of k-fold cross-validation which sliced and dices the data into k-different parts and generates training and test datasets on the go.


I used a deep learning technique, Convolutional Neural Networks (CNN), which is primarily used for image and video processing. Video processing is one of the most common applications of CNNs as it is the "eyes and ears" of a Self-Driving Car.

