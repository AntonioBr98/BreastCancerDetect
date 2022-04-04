# BreastCancerDetect

## Introduction
The aim of my project is to put into practice what i learned about Machine Learning
by using CreateML and CoreML (with Vision and UIKit integrations).
Below will be shown all the steps that I did to create a ML model for breast cancer detection.

## Breast Cancer
Breast cancer is the most commonly occurring cancer in women and the second most common cancer overall.
There were over 2 million new cases in 2021. 

## Data Description
Mammography images of INbreast database was originally collected from Centro Hospitalar de S. Joao [CHSJ], Breast center, Porto.
INbreast database collects data from Aug. 2008 to July 2010, which contains 115 cases with a total of 410 images.
Among them, 90 cases were women with disease on both breasts. 
There are four different types of breast diseases recorded in the database, including Mass, 
Calcification, Asymmetries, and Distortions.

## Data Collection
Combining four breast density categories and breast benign or malignant status, therefore, 
there are 8 categories in our classification task. The eight categories are:

- (1) The category of breast density is 1 and breast mass is benign (Density1+Benign) <br/>
- (2) The category of breast density is 1 and breast mass is malignant (Density1+Malignant) <br/>
- (3) The category of breast density is 2 and breast mass is benign (Density2+Benign) <br/>
- (4) The category of breast density is 2 and breast mass is malignant (Density2+Malignant) <br/>
- (5) The category of breast density is 3 and breast mass is benign (Density3+Benign) <br/>
- (6) The category of breast density is 3 and breast mass is malignant (Density3+Malignant) <br/>
- (7) The category of breast density is 4 and breast mass is benign (Density4+Benign) <br/>
- (8) The category of breast density is 4 and breast mass is malignant (Density4+Malignant). <br/>

## Create ML

## Configure the Training Session
I created **two different models**: <br/>

**The first one** is composed by 7632 images of breast cancer divided in 2 classes: Benign and Malignant (125 iterations).

The second one is composed by 6630 images and it’s divided in 8 Classes: there are four different density of breast cancer (300 iterations).

## Train the Image Classifier
Create ML shows its progress in a graph, where the black and gray lines represent the model’s accuracy with the training and validation datasets, respectively.

## Evaluation
First model

Second Model

## Preview
Fist Model 

Second Model

## App + Model 

## Conclusion
Obviously the created model is not very accurate due to the lack of images in the dataset, therefore errors of evaluation can happen.

The aim of this project was to learn CreateML and CoreML, so I can feel satisfied.

## Linkedin: 
https://www.linkedin.com/feed/update/urn:li:activity:6915425877497372672/
