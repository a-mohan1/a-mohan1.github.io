---
layout: single
title: "ML Publications"
permalink: /projects/
classes: wide
header:
  image: "/assets/images/background2.png"
author_profile: true
---

## Deciphering Heartbeat Signatures: A Vision Transformer Approach to Explainable Atrial Fibrillation Detection from ECG Signals

Abstract: Remote patient monitoring based on wearable single-lead electrocardiogram (ECG) devices has significant potential for enabling the early detection of heart disease, especially in combination with artificial intelligence (AI) approaches for automated heart disease detection. There have been prior studies applying AI approaches based on deep learning for heart disease detection. However, these models are yet to be widely accepted as a reliable aid for clinical diagnostics, in part due to the current black-box perception surrounding many AI algorithms. In particular, there is a need to identify the key features of the ECG signal that contribute toward making an accurate diagnosis, thereby enhancing the interpretability of the model. In the present study, we develop a vision transformer approach to identify atrial fibrillation based on single-lead ECG data. A residual network (ResNet) approach is also developed for comparison with the vision transformer approach. These models are applied to the Chapman--Shaoxing dataset to classify atrial fibrillation, as well as another common arrhythmia, sinus bradycardia, and normal sinus rhythm heartbeats. The models enable the identification of the key regions of the heartbeat that determine the resulting classification, and highlight the importance of P-waves and T-waves, as well as heartbeat duration and signal amplitude, in distinguishing normal sinus rhythm from atrial fibrillation and sinus bradycardia. 

This work was accepted as a lecture presentation at IEEE EMBC 2024. The paper is available [here](https://arxiv.org/abs/2402.09474) and on [IEEE Xplore](https://ieeexplore.ieee.org/document/10782666).

## RhythmBERT: A Self-Supervised Language Model Based on Latent Representations of ECG Waveforms for Heart Disease Detection

Abstract: Electrocardiogram (ECG) analysis is crucial for diagnosing heart disease, but most self-supervised learning methods treat ECG as a generic time series, overlooking physiologic semantics and rhythm-level structure. Existing contrastive methods utilize augmentations that distort morphology, whereas generative approaches employ fixed-window segmentation, which misaligns cardiac cycles. To address these limitations, we propose RhythmBERT, a generative ECG language model that considers ECG as a language paradigm by encoding P, QRS, and T segments into symbolic tokens via autoencoder-based latent representations. These discrete tokens capture rhythm semantics, while complementary continuous embeddings retain fine-grained morphology, enabling a unified view of waveform structure and rhythm. RhythmBERT is pretrained on approximately 800,000 unlabeled ECG recordings with a masked prediction objective, allowing it to learn contextual representations in a label-efficient manner. Evaluations show that despite using only a single lead, RhythmBERT achieves comparable or superior performance to strong 12-lead baselines. This generalization extends from prevalent conditions such as atrial fibrillation to clinically challenging cases such as subtle ST-T abnormalities and myocardial infarction. Our results suggest that considering ECG as structured language offers a scalable and physiologically aligned pathway for advancing cardiac analysis.

This work was accepted at ICASSP 2026. The paper is available [here](https://arxiv.org/abs/2602.23060).

# Projects

## Brain Tumor Classification Using Convolutional Neural Networks

In this project, I implemented CNNs for the classification of brain tumors from MRI images. I experimented with several CNN architectures, and also applied the LeNet-5 and ResNet architectures, as well as transfer learning with the VGG-16 model.  For hyperparameter optimization, I applied grid search cross-validation, random search and Bayesian optimization with the Keras Tuner, and AutoKeras. Here is my [LinkedIn article](https://www.linkedin.com/pulse/deep-learning-brain-tumor-classification-aruna-mohan/) describing this work. My code is available [here](https://github.com/a-mohan1/CNN-image-classification).

## Time Series Analysis of Air Travel and the Impact of COVID-19

I implemented time series forecasting methods based on autoregressive and moving average models to forecast air passenger numbers, for comparing against historical and recent data on air travel. Here is my [LinkedIn article](https://www.linkedin.com/pulse/time-series-analysis-air-travel-impact-covid-19-aruna-mohan/) describing this project. My code is available at this [link](https://github.com/a-mohan1/Time-series-analysis).

## Predictive Modeling of Car Accidents in Seattle Based on Supervised Machine Learning

I applied classification methods based on logistic regression, kNN, decision tree classifiers, and  support vector classifiers, to predict car accidents using data available from the [Seattle DOT website](https://gisdata.seattle.gov/server/rest/services/SDOT/SDOT_Collisions/MapServer/0). Here is my 
[LinkedIn article](https://www.linkedin.com/pulse/predictive-modeling-car-accidents-seattle-aruna-mohan/) about this project, and my code is available [here](https://github.com/a-mohan1/ML-Classification).
