# Facial Expression Recognition 

Download Dataset from [my kaggle profile](https://www.kaggle.com/rahulgaikwad2010/emotion-detection) 

In the project, we will be working with a specified dataset of images. we will then explore the data and try the statistical learning approaches that we have covered in this course to tackle the task associated with the dataset. The statistical approaches should cover both conventional machine learning (i.e. not deep learning), from the first half of the unit, and deep learning from the second half. A goal of the project is to explore the approaches we've leant, or perhaps beyond those, in order to build a high-performing system.

# Table Of Contents
-  [Project Structure Overview](#project-structure-overview)
-  [Introduction](#introduction)
-  [Project Goal](#project-goal)
-  [Data Set](#data-set)
-  [Version](#version)
-  [Author](#author)

<br/>

### Project Structure Overview
```
├── Facial Expression Recognition Deep Learning
|  ├── dataset       - this folder contains training & testing data.
|  │    ├──  PrivateTest_data_images.npy
|  |    ├──  PublicTest_data_images.npy
|  |    ├──  Training_data_images.npy (Omitted Because > 25 MB)
|  |    └──  Training_data_labels.npy
|  │
└────── Facial Expression Recognition.ipynb
```

<br/>

### Introduction

In the project, we will be working with a specified dataset of images.  we will then explore the data and try the statistical learning approaches that we have covered in this course to tackle the task associated with the dataset.  The statistical approaches should cover both conventional machine learning (i.e. not deep learning), from the first half of the unit, and deep learning from the second half.  A goal of the project is to explore the approaches we've leant, or perhaps beyond those, in order to build a high-performing system.

### Project Goal

The goal of this project is to predict the expression on the face.  The expression labels are standard ones used in psychology research: **angry, disgusted, fearful, happy, sad, surprised, neutral.**


We will using the ML/DL models in the analysis which are stated below as:

#### Conventional Models

1. Support Vector Machines (SVM)
2. Light Gradient Boosting Machine (LGBM)


#### Deep Learning

1. Convolutional Neural Network (Part 1)
2. Convolutional Neural Network (Part 2)


### Data Set

The dataset have images of the faces which have the expressions or 7 classes as angry, disgusted, fearful, happy, sad, surprised, neutral.The Images pixel size is 48 x 48 grey scaled. 

<b>Train data</b> - (9328, 48, 48)

<b>Public Test data</b> - (1136, 48, 48)
    
<b>Private Test data</b> - (1153, 48, 48)

<br/>

## Version

1.0.0 

<br/>

## Author

* **Rahul Gaikwad** - Initial work and development

<br/>

I welcome your questions. Write to rahul.gaikwad2010@gmail.com

<br/>
