---
modal-id: 14
title: GazeToGrasp
topics: Virtual Reality, Machine Learning, Prosthesis & Orthosis
blurb: 'GazeToGrasp is a project that strives to make grasping objects more accessible to upper-limb prosthesis users. Many prosthesis users use compensatory strategies to make up for the range of motion deficiency in a wrist-locked prosthetic limb and experience additional cognitive load when using wrist-locked upper limb prostheses. GazeToGrasp uses deep learning to create a predictive control strategy for a virtual upper-limb prosthesis with the goal of assisting prosthesis users in performing grasping tasks. '
header: /media/gazetograspHelps.png
thumbnail: /media/gazetograspDemo.png
people: Maxim Karrenbach, Eric Rombokas
permalink: gazetograsp
---

## Introduction
In object grasping, users of wrist-locked prostheses are often compelled to perform compensatory movements due to the lacking range of motion of a wrist locked prosthesis. This can cause overuse of other systems, like the shoulder or intact hand, and causing additional cognitive load. GazeToGrasp leverages deep learning and gaze-centered datasets gathered on human subjects to create predictive control strategies capable of predicting optimal grasps of objects. 

## Data Collection
We collect gaze-centered vision data from intact human subjects performing tasks of picking up objects in a virtual environment. A deep learning algorithm is trained on this data, learning a relationship between gaze of users and the optimal affordances of an object based on its orientation.
![Data Collection Objects](/media/gazetograspData.png)

## User Study
Implementing this algorithm into a virtual prosthesis, a user study is used to compare performance of this predictive control strategy against a wrist-locked prosthesis. Shoulder compensation and decision time are both reduced for the implementation of the predictive control.
![User Study Results](/media/gazetograspUser.png)
<video src="https://user-images.githubusercontent.com/40015433/171765558-e5afe6fb-37db-4457-aa37-189e513a2d95.mp4" controls="controls" style="max-width: 730px;">
</video>

## Links
- [Full Text](https://ieeexplore.ieee.org/document/9698069)
- [Video](Coming Soon!)
