---
modal-id: 6
title: Muscle Activation, EMG, and Gestures
topics: Human-Machine Interface, Machine Learning, Virtual Reality
blurb: New gesture-sensing systems use sophisticated cameras and data processing to achieve in-air interaction with computer systems and interaction with virtual and augmented reality. A key feature of human movement, however, is invisible to these cameras- the activation of the muscles. Electromyography (EMG) can sense the activation of muscles, but it is difficult to infer pose and movement from EMG alone. These two complementary technologies can be combined to improve human-machine interaction.
header: emgThumbnail.png
thumbnail: emgThumbnail.png
people: Eric Rombokas, Pornthep Preechayasomboon
permalink: muscleGestures
---
## Introduction
Vision-based gesture and pose detecting systems combined with EMG muscle sensing present the opportunity to create extremely capable multimodal human-machine interaction systems.

## EMG array armband
We we are trying to estimate hand kinematics and intent from a forearm-worn EMG array. For data collection, Jom Preechayasomboon built a custom 8-channel EMG armband from scratch based on the ADS1299. The electrodes are 3D printed from electrically conductive TPU. The nRF-based wireless communication, based off of technology developed for our haptics projects, enable low latency (1 ms) streaming to a USB dongle. We stream 1000 Hz data directly to a Meta Quest 2 so we can collect hand tracking data and EMG signals simultaneously, all locally on the headset. This is great for deployment for user studies without the hassle of hardware setup, just plug-n-play.

<p><img src="/media/emgBandPrototype.jpg" alt="EMG Band Prototype" /></p>

<video width="100%" controls="">
     <source src="//user-images.githubusercontent.com/25041773/157564522-c7b8c7fa-c504-42df-85a7-2076a20988bc.mp4" />
</video>


<p>Pornthep also made this sick data visualizer for the collected EMG and kinematic data.</p>

<video width="100%" controls="">
     <source src="//user-images.githubusercontent.com/25041773/157564826-d1eea89a-9a4d-4ef1-ba22-0f7e73195a99.mp4" />
</video>

<p>And lastly, a rather unrelated, proof-of-concept of EMG + Physics Hands 🤝</p>

<video width="100%" controls="">
     <source src="//user-images.githubusercontent.com/25041773/159648690-ab742d24-0c57-467c-bf16-f396df00cb52.mp4" />
</video>

For more information follow Pornthep's <a href="https://pornthep.com/">website</a>


## Improvement of EMG calibration
Current use of EMG is plagued by the spectre of calibration. A major factor of this is "normalization," or removing the sensitivity of the signal to scale variation due to factors like differences in skin conductance. The current practice is to normalize the signals by the signal obtained during "maximal voluntary contraction" (MVC). We have demonstrated that MVC is highly senstive to pose, and demonstrate a means for correcting for this effect using the pose-sensing camera (Intel Perceptual Computing.)

## Myometric Authentication
Gesture computing could support "movement passwords," or special combinations of movements and poses used as a password. These would be vulnerable, however, to video recording and mimicry. If the visual modality were coupled with EMG sensing, there could exist a secret channel that augments the gesture password and secures it against mimicry.

See this <a href="media/JustEMGSlidesFromCSNEPresentation.pptx">slide deck </a> for more details.
