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
<img width="648" alt="Screenshot 2022-03-30 at 17 06 45" src="https://user-images.githubusercontent.com/92536025/161567715-e17cc4df-9d0a-44a2-a6db-333038498974.png">


## Configure the Training Session
I created **two different models**: 
### The first one 
is composed by 7632 images of breast cancer divided in 2 classes: Benign and Malignant (125 iterations).
<img width="841" alt="Screenshot 2022-03-30 at 17 08 20" src="https://user-images.githubusercontent.com/92536025/161568002-f4231267-c8dc-40ca-883a-f113fa8d9c36.png">

### The second one 
is composed by 6630 images and it’s divided in 8 Classes: there are four different density of breast cancer (300 iterations).
<img width="872" alt="Screenshot 2022-03-30 at 17 11 07" src="https://user-images.githubusercontent.com/92536025/161568068-12e95037-10a6-4c7c-84c6-ce22182efa00.png">

## Train the Image Classifier
Create ML shows its progress in a graph, where the black and gray lines represent the model’s accuracy with the training and validation datasets, respectively.
<img width="866" alt="Screenshot 2022-04-04 at 16 40 22" src="https://user-images.githubusercontent.com/92536025/161568715-72cc628f-dbd9-48ac-bc85-5457f578c304.png">


## Evaluation
### First model
<img width="866" alt="Screenshot 2022-03-30 at 17 17 51" src="https://user-images.githubusercontent.com/92536025/161568843-6cda718a-c34e-436b-9c9a-7070abaf3598.png">


### Second Model
<img width="866" alt="Screenshot 2022-03-30 at 17 17 57" src="https://user-images.githubusercontent.com/92536025/161568930-04b183e2-3a8d-4873-aa66-f10d511a4a4f.png">


## Preview
### Fist Model 
<img width="847" alt="Screenshot 2022-03-30 at 17 19 49" src="https://user-images.githubusercontent.com/92536025/161569268-a3ef7b72-06da-491a-a2ec-99921c589eb4.png">


### Second Model
<img width="854" alt="Screenshot 2022-03-30 at 17 20 14" src="https://user-images.githubusercontent.com/92536025/161569303-b136e487-3735-49b3-8f64-349426653bdd.png">


## App + Model 
<img width="399" alt="Screenshot 2022-03-31 at 00 01 22" src="https://user-images.githubusercontent.com/92536025/161569643-f86937df-0125-4f61-8ac0-33ae9b5e8cbf.png">

<img width="409" alt="Screenshot 2022-03-30 at 23 52 48" src="https://user-images.githubusercontent.com/92536025/161569351-6295405b-d1bd-4aa3-826f-bd52a73d091a.png">

## Conclusion
Obviously the created model is not very accurate due to the lack of images in the dataset, therefore errors of evaluation can happen.

The aim of this project was to learn CreateML and CoreML, so I can feel satisfied.

## Linkedin: 
https://www.linkedin.com/feed/update/urn:li:activity:6915425877497372672/
