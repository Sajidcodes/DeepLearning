
![Adversarial attack](url)

![image](https://github.com/Sajidcodes/DeepLearning/assets/101083684/ec96a5f3-1cc1-44d5-8dfa-125a89dfed62)

# Task Overview
Welcome to the Adversarial Attack challenge! In this task, I performed a non-targeted attack on pre-trained models using the Iterative-Fast Gradient Sign Method (i-FGSM) and its variants. The task involves manipulating benign images from the CIFAR-10 dataset to generate adversarial samples while adhering to specific constraints.

# Methodologies to be Familiar With
Before diving into the task, make sure you understand the following methodologies:

Attack Objective: Non-targeted attack
Attack Constraint: L-infinity norm and Parameter ε
Attack Algorithm: i-FGSM attack
Attack Schema: Black box attack (perform the attack on a proxy network)

Accuracy after attack = 0.0000%
Choose any proxy network to attack the black box. Pytorchcv provides multiple models pretrained on CIFAR-10

Implemented non-targeted iFGSM from scratch.

# Dataset Information
Dataset: CIFAR-10

Classes: 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
Images: 20 for each class
Image Size: 32x32 RGB

# Evaluation
Parameter ε: Fixed to 8
Distance Measurement: L-infinity norm

Feel free to reach out if you have any questions. Good luck!





