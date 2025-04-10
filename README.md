# Handwritten Digit Recognition

**Project Context:**  
This Project was done as part of **Course, CSL2050:Pattern Recognition and Machine Learning at Indian Institute of Technology,Jodhpur** in the spring semester of the Academic Year 2024-25. 

---

## Table of Contents

1. [Project Description](#project-description)
2. [Methods and Performance](#methods-and-performance)
3. [Video Walkthrough](#video-walkthrough)
4. [How to Run the Project](#how-to-run-the-project)
5. [Contributors](#contributors)

---

## Project Description

This project focuses on building a **Handwritten digit recognition system**. The goal of the project is to design and implement different machine learning models capable of recognizing and classifying these handwritten digits with high accuracy and comparing their efficiencies and performance.
#### Dataset Used:
The dataset used in this project is the **MNIST (Modified National Institute of Standards and Technology)** dataset, which is a large collection of handwritten digits. The MNIST dataset consists of **60,000 training images and 10,000 testing images, each of size 28x28 pixels**. The images are labeled with the corresponding digit (0-9). This dataset is widely used for training image recognition models and serves as a standard benchmark for evaluating machine learning algorithms, especially in the field of computer vision.

---

## Methods and Performance

In this project, we implemented six different machine learning algorithms for handwritten digit recognition on the MNIST dataset. Each algorithm was trained and evaluated using the same training and testing data, and the results were compared in terms of accuracy.

1. **K-Nearest Neighbors (KNN)**  
   KNN is a non-parametric algorithm that classifies data points based on the majority class of their nearest neighbors. The distance metric, such as Euclidean distance, is used to measure the proximity between data points. Although KNN is simple, it can be computationally expensive for large datasets, as it requires calculating distances for each query point.

2. **Support Vector Machine (SVM)**  
   SVM is a powerful classification algorithm that works by finding the optimal hyperplane that best separates data points of different classes. It can handle both linear and non-linear classification problems by using different kernel functions.Support Vector Machine (SVM) is highly effective often achieving remarkable accuracy in complex tasks, especially when handling high-dimensional data. Its ability to separate classes with a clear margin makes it a robust choice for tasks like handwritten digit recognition.

3. **Random Forest**  
   Random Forest is an ensemble learning method that constructs multiple decision trees and combines their predictions. Each tree in the forest is trained on a random subset of the data, which helps reduce overfitting. Random Forest is known for its high accuracy and robustness, especially for classification tasks.

4. **Logistic Regression**  
   Logistic Regression is a linear model that is commonly used for binary classification tasks. However, it can be extended to multi-class problems, as in this project, using a one-vs-rest strategy. The algorithm estimates the probability of each class, and the class with the highest probability is chosen as the predicted label.

5. **Decision Tree**  
   Decision Trees are a simple yet effective classification algorithm that splits the dataset into subsets based on feature values. The tree is constructed recursively by choosing the feature that best splits the data at each step. Although decision trees are interpretable, they can suffer from overfitting, especially with deep trees.

6. **Naive Bayes**  
   Naive Bayes is a probabilistic classifier based on Bayes' Theorem. It assumes that the features are independent of each other given the class label, which is why it's called "naive." Despite its simplicity, Naive Bayes often performs surprisingly well for classification tasks like digit recognition.

### Results

The following table summarizes the accuracy of each algorithm on the MNIST test set:

| Algorithm                | Accuracy (%) |
|--------------------------|--------------|
| K-Nearest Neighbors (KNN) | 86.53         |
| Support Vector Machine (SVM) | 95.44       |
| Random Forest            | 92.25       |
| Logistic Regression      | 92.57        |
| Decision Tree            | 86.52         |
| Naive Bayes              | 88.15         |

As seen in the table, **SVM** achieved the highest accuracy, followed by **Logistic Regression** and **Random Forest**. 




---

## Video Walkthrough

Here’s a walkthrough of the project explaining how it works and the features it offers:
**(Please set quality to minimum 480p.)**
[![Video Thumbnail](https://img.youtube.com/vi/GoP_YK_526g/0.jpg)](https://www.youtube.com/watch?v=GoP_YK_526g)


---
## How to run the project
You just need to go the following link, there you can draw a digit with a marker available and you can see the results.
Link for web demo of the project:
[Live Demo]()

---
## Contributors:
|S. No.|Team Member | Contribution| 
|--|--|--|
|1.| Nitin Verma| SVM Implementation | 
|2.|Nitesh |Logistics Regression model| 
|3.| Shruti Sunil Vibhute| Random Forest| 
|4.|Saurabh Kumar |Naive Bayes Model| 
|5.|Vanshita Jeenwal| Decision Tree| 
|6.|Mallam Vishnu Priya|KNN |
