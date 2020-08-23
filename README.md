# Pneumonia-Detection-using-Computer-Vision

Capstone Project for Pneumonia Detection using Computer Vision.

## Problem Statement

Pneumonia detection requires review of a chest radiograph (CXR) by highly trained specialists and confirmation through clinical history, vital signs and laboratory exams. Pneumonia usually manifests as an area or areas of increased opacity on CXR. However, the diagnosis of pneumonia on CXR is complicated because of a number of other conditions in the lungs such as fluid overload (pulmonary edema), bleeding, volume loss (atelectasis or collapse), lung cancer, or post-radiation or surgical changes. Outside of the lungs, fluid in the pleural space (pleural effusion) also appears as increased opacity on CXR. When available, comparison of CXRs of the patient taken at different time points and correlation with clinical symptoms and history are helpful in making the diagnosis. A number of factors such as positioning of the patient and depth of inspiration can alter the appearance of the CXR, complicating interpretation further.

## Objective

In this capstone project, the goal is to build a pneumonia detection system, to locate the position of inflammation in an image. The project aims at automating Pneumonia screening in chest radiographs, providing affected area details through bounding box. This can assist physicians to make better clinical decisions or even replace human judgement in certain functional areas of healthcare (eg, radiology).

## Data
Medical images are stored in a special format called DICOM files (*.dcm). They contain a combination of header metadata as well as underlying raw image arrays for pixel data. The data used in this project can be downloaded from the following link

https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data

## Implementation Steps

**Pre-Processing, Data Visualization, EDA**
* Exploring the given Data files, classes and images of different classes.
* Dealing with missing values
* Visualization of different classes
* Analysis from the visualization of different classes.

**Model Building**
* Building a pneumonia detection model starting from basic CNN and then improving upon it.
* Train the model
* To deal with large training time, save the weights so that you can use them when training the model for the second time without starting from scratch. 

**Test the Model, Fine-tuning and Repeat**
* Test the model and report as per evaluation metrics 
* Try different models 
* Set different hyper parameters, by trying different optimizers, loss functions, epochs, learning rate, batch size, checkpointing, early stopping etc. for these models to fine-tune them 
* Report evaluation metrics for these models along with your observation on how changing different hyper parameters leads to change in the final evaluation metric.
