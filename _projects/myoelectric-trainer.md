---
modal-id: 3
title: Myoelectric Trainer
topics: Prosthesis & Orthosis, Virtual Reality
blurb: Despite the incredible cost of a state of the art upper limb prosthesis, they are often abandoned by users who feel they do not match their needs. Effective use of these prostheses requires advanced training methods - which has unfortunately received relatively little focus.
header: myoelectric-trainer.png
thumbnail: myoelectric-trainer.png
people: David Boe
---
## Description
In current practice, reimbursement, lack of experience, and the increasing complexity of prosthetic devices limit patient access to healthcare professionals qualified to administer prosthetic training. We will lower the barrier to access by developing a self-guided prosthetic training application that teaches the fundamental skills required to control a state of the art myoelectric prosthesis. Training will be delivered in a gamified virtual environment that motivates the patient to engage in a wide variety of activities with his or her virtual prosthesis. Aside from providing enhanced preprosthetic training, simulated ownership of a missing limb can be used to investigate potential benefits to psychological well-being and pain management post-amputation.

## Aims
**Aim 1:** Achieve control of simulated prosthetic hand with realistic behavior and constraints.

**Aim 2:** Develop a training protocol that is relevant to rehabilitation priorities.

**Aim 3:** Demonstrate improvement in upper limb functional outcomes with simulated prosthesis and real prosthesis.

## Methods
The following must be accomplished

* Motion tracking of the residual limb
* EMG signal capture
* Visual display of environment
* Transformation of EMG signal to control signal
* Controls implemented to guide prosthesis behavior
* Actuated prosthetic hand
* Physics-based virtual environment
* Rehabilitation relevant task/game to complete
* Sensory feedback of virtual prosthesis

EMG data is collected with an 8 channel Myo armband, and motion tracking is done using off the shelf VR handheld controllers like the Oculus Touch (moving to Vive Puck). Unity engine provides integration of sensors and renders a believable visual environment. EMG signal actuates a simulated prosthetic hand during virtual training. A variety of control methods are available to the user - thus enabling the customization their prosthesis to suit their needs.
