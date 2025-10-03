---
layout: single
title: "ML Projects"
permalink: /projects/
classes: wide
header:
  image: "/assets/images/background2.png"
author_profile: true
---

I have worked on several projects applying machine learning and deep learning in my work, as part of coursework, and for self-learning. Here are some of my published and/ or personal data science projects.

## Deciphering Heartbeat Signatures: A Vision Transformer Approach to Explainable Atrial Fibrillation Detection from ECG Signals

Abstract: Remote patient monitoring based on wearable single-lead electrocardiogram (ECG) devices has significant potential for enabling the early detection of heart disease, especially in combination with artificial intelligence (AI) approaches for automated heart disease detection. There have been prior studies applying AI approaches based on deep learning for heart disease detection. However, these models are yet to be widely accepted as a reliable aid for clinical diagnostics, in part due to the current black-box perception surrounding many AI algorithms. In particular, there is a need to identify the key features of the ECG signal that contribute toward making an accurate diagnosis, thereby enhancing the interpretability of the model. In the present study, we develop a vision transformer approach to identify atrial fibrillation based on single-lead ECG data. A residual network (ResNet) approach is also developed for comparison with the vision transformer approach. These models are applied to the Chapman--Shaoxing dataset to classify atrial fibrillation, as well as another common arrhythmia, sinus bradycardia, and normal sinus rhythm heartbeats. The models enable the identification of the key regions of the heartbeat that determine the resulting classification, and highlight the importance of P-waves and T-waves, as well as heartbeat duration and signal amplitude, in distinguishing normal sinus rhythm from atrial fibrillation and sinus bradycardia. 

This work was accepted as a lecture presentation at IEEE EMBC 2024. The article is available [here](https://arxiv.org/abs/2402.09474).

## Brain Tumor Classification Using Convolutional Neural Networks

In this project, I implemented CNNs for the classification of brain tumors from MRI images. I experimented with several CNN architectures, and also applied the LeNet-5 and ResNet architectures, as well as transfer learning with the VGG-16 model.  For hyperparameter optimization, I applied grid search cross-validation, random search and Bayesian optimization with the Keras Tuner, and AutoKeras. Here is my [LinkedIn article](https://www.linkedin.com/pulse/deep-learning-brain-tumor-classification-aruna-mohan/) describing this work. My code is available [here](https://github.com/a-mohan1/CNN-image-classification).

## Time Series Analysis of Air Travel and the Impact of COVID-19

I implemented time series forecasting methods based on autoregressive and moving average models to forecast air passenger numbers, for comparing against historical and recent data on air travel. Here is my [LinkedIn article](https://www.linkedin.com/pulse/time-series-analysis-air-travel-impact-covid-19-aruna-mohan/) describing this project. My code is available at this [link](https://github.com/a-mohan1/Time-series-analysis).

## Predictive Modeling of Car Accidents in Seattle Based on Supervised Machine Learning

I applied classification methods based on logistic regression, kNN, decision tree classifiers, and  support vector classifiers, to predict car accidents using data available from the [Seattle DoT website](https://gisdata.seattle.gov/server/rest/services/SDOT/SDOT_Collisions/MapServer/0). Here is my 
[LinkedIn article](https://www.linkedin.com/pulse/predictive-modeling-car-accidents-seattle-aruna-mohan/) about this project, and my code is available [here](https://github.com/a-mohan1/ML-Classification).
