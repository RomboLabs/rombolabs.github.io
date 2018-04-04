---
modal-id: 9
title: Smart Prosthesis
topics: Machine Learning, Prosthesis
blurb: Could a prosthesis learn from examples to adapt to any real-world scenario, much like humans do? Such a self-driving prosthesis would be a radical shift from the current state of affairs where assistive devices operate under strict “modes” of operation with terrain specific movement profiles. 

header: ankle_prosthesis.jpg
thumbnail:ankle_prosthesis.jpg
people: Vijeth Rai, Eric R
permalink: deepProsthesis
---
<img src="/images/Architecture.png" alt="Drawing" style="width: 800px;"/>

## Introduction
Most state-of-the-art prosthetic controllers define modes of operation corresponding to terrain types such as flat-ground walking or stair ascent. But humans don’t think in terms of discrete modes for locomotion. Instead, humans optimize and select complex unique movements based on past experiences of navigating similar conditions. However, given the range of possible scenarios, an all-encompassing controller has been hard to implement.

We propose to use computer vision, inertial sensors and techniques from deep learning to train a system to generate movement controls for a prosthesis based on the movements observed in real scenarios. Such an example-based approach requires a copious amount of data but it provides the capability to generate movement that might be di?cult for us to explicitly model.

## Methods:	 	 	
### Phase 1- Kinematics :
Whole body gait kinematics will be collected using wireless inertial sensors (Xsens Inc). The dataset will include unstructured movements and activities from multiple users. A Long Short-Term Memory (LSTM) network will be trained to estimate instantaneous ankle kinematics.

### Phase 2 - Kinematics + Vision :
Scenarios such as obstacle avoidance and transition to stair ascent will need a glimpse of upcoming terrains. Whole body gait kinematics and raw image data from a head-mounted camera will be used to train a Convolutional Neural Network (CNN) + LSTM to estimate instantaneous kinematics, and also to predict upcoming ones.


