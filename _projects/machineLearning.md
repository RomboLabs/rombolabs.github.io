---
modal-id: 422
title: Machine Learning for Control
topics: Machine Learning 
blurb: Almost every application we work on uses machine learning techniques. We focus on data-driven discovery of representations that help us understand sensor data and control complex devices. 

header: machineLearningSplash.png
thumbnail: machineLearningSplash.png
people: Just about all Rombolabs members over all time
permalink: machineLearning
---


## Overview
Robotic state estimation, wearable motion capture, egocentric camera data, optical hand tracking, wearable gaze tracking, robotic prosthetic limbs, and more! All of these applications generate complex time series data that are difficult to model using traditional techniques. Luckily, there are now outrageously powerful data science methods that learn to represent these high-dimensional and unpredictable datastreams. 

## Latent embeddings
One of our primary areas of focus is in creating low-dimensional embeddings of high-dimensional time series data, such as body tracking data. We primarily use unsupervised and self-supervised neural networks that are trained to concisely summarize the regularities in the data. One advantage of these methods is that the low-dimensional representations can aid in human understanding of the data. They also provide a low-dimensional space to plan and control in. 

<img src="/media/gaitAutoencoders.png">

<img src="/media/activityLatent.png">

## Data-driven robotic control

When the environment is uncertain, or when the dynamics of the robot are complex, it becomes difficult to use traidtional, physics-based models for control. We develop new methods for using real recordings of robotic motion and sensors to enable new controllers that leverage the power of deep learning representations and model-predictive optimal control. The applications range from [soft sensor-actuator enabled robots](https://www.mdpi.com/2076-0825/10/2/30) to [Model Predictive Policy Improvement](https://arxiv.org/abs/1503.00330) using learned dynamics models and beyond. 
  
![The ACT Hand is a tendon-driven biomechanical robot](Act Hand.png)

![Model-predictive Policy Improvement (MPPI) parallelized on a GPU using data-derived dynamic models](QuadSmasherChasing.wmv)

