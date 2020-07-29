# Overview

- The goal of the project was to build an Intrusion Detection System (IDS) that can classify the connections in the dataset as an attack or a normal connection
- This was a Binary Classification problem in which we used Fully Connected Neural Networks and Convolutional Neural Networks to classify the target feature
- Broke down the attacks of the target feature into different types and built a model that classified an attack connection to its specific attack type. A Multi-Class Classification used Convolutional Neural Networks was applied to classify the target features.

# Methodology

- Applied Data Processing for Data Frame
- One-hot encoded the 9 categorical features of the dataset.
- Normalized all the numeric features of the dataset using z-scores.
- Made all the different types of attacks into one value, attack, to make the problem a Binary Classification problem.
- Used Logistic Regression for Feature Importance Analysis.
- Dropped the 102 features that had a coefficient of between -1 and 1.
- Built a CNN with 9 total layers with two convolutional layers with 32 kernels and 64 kernels and a kernel size of 1 by 5 for multi-class classification.

# Result

[![Screen-Shot-2020-07-28-at-8-02-39-PM.png](https://i.postimg.cc/hG3cNcZz/Screen-Shot-2020-07-28-at-8-02-39-PM.png)](https://postimg.cc/NyT3HqcB)