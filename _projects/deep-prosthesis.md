---
modal-id: 9
title: Coordinated Movement Prosthesis Control
topics: Machine Learning, Prosthesis & Orthosis
blurb: Could a prosthesis learn from examples to adapt to any real-world scenario, much like humans do? Such a self-driving prosthesis would be a radical shift from the current state of affairs where assistive devices operate under strict “modes” of operation with terrain specific movement profiles.

header: Network_basic.png
thumbnail: Network_basic.png
people: Vijeth Rai, Eric R
permalink: deepProsthesis
---
<!-- ![lstm_arch](/img/portfolio/Network_basic.png) -->


## Introduction
Most state-of-the-art prosthetic controllers define modes of operation corresponding to terrain types such as flat-ground walking or stair ascent. But humans don’t think in terms of discrete modes for locomotion. Instead, humans optimize and select complex unique movements based on past experiences of navigating similar conditions. However, given the range of possible scenarios, an all-encompassing controller has been hard to implement.

We are using computer vision, inertial sensors and deep learning to train a system to generate movement controls for a prosthesis based on the movements observed in real scenarios. Such an example-based approach requires a copious amount of data but it provides the capability to generate movement that might be difficult for us to explicitly model.

For the user of a coordinated movement prosthesis controller, the prosthetic limb responds appropriately in response to the rest of the body.

## Methods:	 	 	
### Phase 1- Kinematics :
Whole body gait kinematics will be collected using wireless inertial sensors (Xsens Inc). The dataset will include unstructured movements and activities from multiple users. A Long Short-Term Memory (LSTM) network will be trained to estimate instantaneous ankle kinematics.

![Transition](/img/portfolio/Trans_flat_SD.png)

### Phase 2 - Kinematics + Vision :
Scenarios such as obstacle avoidance and transition to stair ascent will need a glimpse of upcoming terrains. Whole body gait kinematics and raw image data from a head-mounted camera will be used to train a Convolutional Neural Network (CNN) + LSTM to estimate instantaneous kinematics, and also to predict upcoming ones.
