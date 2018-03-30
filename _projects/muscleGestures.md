---
modal-id: 6
title: Muscle Activation and Gestures
topics: Human-Machine Interface, Machine Learning
blurb: New gesture-sensing systems use sophisticated cameras and data processing to achieve in-air interaction with computer systems. A key feature of human movement, however, is invisible to these cameras- the activation of the muscles. Electromyography (EMG) can sense the activation of muscles, but it is difficult to infer pose and movement from EMG alone. These two complementary technologies can be combined to improve human-machine interaction.
header: emgGestureSetup.png
thumbnail: emgGestureSetup.png
people: Eric R. 
---
## Introduction
Vision-based gesture and pose detecting systems combined with EMG muscle sensing present the opportunity to create extremely capable multimodal human-machine interaction systems. 

## Improvement of EMG calibration
Current use of EMG is plagued by the spectre of calibration. A major factor of this is "normalization," or removing the sensitivity of the signal to scale variation due to factors like differences in skin conductance. The current practice is to normalize the signals by the signal obtained during "maximal voluntary contraction" (MVC). We demonstrate that MVC is highly senstive to pose, and demonstrate a means for correcting for this effect using the pose-sensing camera (Intel Perceptual Computing.) 

## Myometric Authentication
Gesture computing could support "movement passwords," or special combinations of movements and poses used as a password. These would be vulnerable, however, to video recording and mimicry. If the visual modality were coupled with EMG sensing, there could exist a secret channel that augments the gesture password and secures it against mimicry.

See this <a href="media/JustEMGSlidesFromCSNE.ppt">slide deck </a> for more details.

