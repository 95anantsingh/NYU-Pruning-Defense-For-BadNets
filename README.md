# Pruning Defense against Badnets
This repository contains code and resources for implementing a pruning defense against badnets in neural networks.

## Overview
Pruning is a defense against badnets that involves removing or "pruning" certain connections or units in a neural network model. This can be done by identifying connections or units that are not contributing significantly to the model's performance, and removing them in order to make the model more efficient and compact.

In the context of defending against badnets, pruning can be used to remove connections or units that are vulnerable to adversarial attacks. By removing these connections or units, the model becomes less susceptible to badnet attacks because the attacker has fewer targets to exploit. Pruning can also make the model more efficient and compact, which can make it more difficult for the attacker to insert malicious samples into the training data without being detected.

## Usage
To use the code in this repository, clone the repository and run the pruning_defense.ipynb. This notebook contains the code for implementing the pruning defense against badnets, and includes instructions for configuring and running the defense.

Data can be pulled from [here](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq).

## Dependencies
This code is written in Python and requires the following dependencies:

- NumPy
- TensorFlow
- Keras

> **Note**: This project was part of Machine Learning for Cyber Security Course at New York University
