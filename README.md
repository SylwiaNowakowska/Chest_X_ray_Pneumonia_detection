# ChestXNet: Pneumonia Detection from Chest X-rays with Convolutional Neural Networks

## Project info
This project is part of AI in healthcare course on Udacity Platform. <br>
https://www.udacity.com/course/ai-for-healthcare-nanodegree--nd320 <br>

The goal of the project is to classify the X-ray scans as pneumonia positive or negative. Different Convolutional Neural Network architectures based on DenseNet121 pre-trained model are built, trained, and evaluated.

## Dataset info
The dataset used in this project: 

NIH Chest X-ray Dataset comprised of 112,120 X-ray images with disease labels from 30,805 unique patients.
The labels include 14 pathologies and were extracted using Natural Language Processing (NLP) from radiological reports. <br>
<br>
Detailed info: https://www.kaggle.com/nih-chest-xrays/data 

## Project files
 1. EDA (exploratory data analysis) <br><br>
 2. Build and train model: <br>
  &ensp; -  Processing metadata <br>
  &ensp; -  Creating training, validation and test datasets <br>
  &ensp; -  Comparison of demographic distributions in the training, validation and test datasets <br>
  &ensp; -  Building of different models, their training and evaluation <br>
  &ensp; -  Model performance summary <br>
  &ensp; -  Next steps <br><br>
 3. Clinical workflow intergration: <br>
  &ensp; - checking relevant DICOM matadata <br>
  &ensp; - pre-processing image for the model <br>
  &ensp; - loading trained model and its weights <br>
  &ensp; - predicting the class <br><br>
  4. FDA submission: <br>
  &ensp; -  intended use statement <br>
  &ensp; -  indication for use <br>
  &ensp; -  device limitations <br>
  &ensp; -  clinical impact of performance <br>
  &ensp; -  algorithm architecture, training and validation description <br>
  &ensp; -  database used for algorithm development <br>
  &ensp; -  ground truth description <br>


