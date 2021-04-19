# About Me

I am an undergraduate student at the University of Maryland. I am expecting to graduate in May of 2021 with two degrees, Bachelor's in Computer Science with a minor Mathematics. Following this I hope to continue my education by pursing a Ph.D. in Reinforcement Learning.

My resume can be found [here](cnalty.github.io/resume.pdf)

# Work History
## [Mukh Technologies](https://www.mukh.com/) - Software Engineering Intern
May 2019 - Present
  * Data and algorithm visualization for facial recognition software
  * Containerization of neural network pipeline in Docker
  * PyTorch training and dataset scripts
  * Updated front end API and reworked backend while maintaining expected functionality



## [Orbit Logic](https://www.orbitlogic.com/) - Systems Engineering Intern
November 2018 - May 2019
  * Regression Testing
  * Automation of Test setup and database restoration

## Honors Thesis - Multi-Task RL Algorithm Comparison on Atari
This paper compares two policy gradient methods for multitask learning (MTL) on the Atari visual environments. These environments are complex and take millions of time steps to learn. This paper investigates Advantage Actor-Critic (A2C) and Proximal Policy Optimization’s (PPO) performance on one, two and four environments from the Arcade Learning Environment. The results show that agents trained with both PPO and A2C have improved performance when trained on multiple tasks when compared to a single task. PPO showed the most consistent improvement and scored the best overall. However, A2C’s improves the most on average compared to its baseline. This shows that the trust-region approximation of PPO may not be as beneficial in MTL as in a single task.

<a href="cnalty.github.io/HonorsThesis.pdf"</a>

# Table of Projects
* [Gait Estimation](#gait-estimation)
* [Character Recognition](#character-recognition)
* [Genetic Algorithms for Training Neural Nets](#genetic-algorithms-for-training-neural-nets)
* [Multi-Task DDQN on Atari](#multi-task-ddqn-on-atari)

# Gait Estimation
This project involved estimating how people walk, known as gait. A pose estimation network was used to extract keypoints on peoples bodies. Using these each persons arm and leg movements were stabalized based on their torso position. The stabalized arm and leg movements were then fitted to a sin wave using Basin-hopping. This method also produces a torso stabilized video of each person walking.

# Character Recognition
This repository contains a simple convolutional neural network for recognition of handwritten digits. Trained and tested using Kaggle distributions of the MNIST dataset and the Kannada MNIST dataset. Accuracy results can be found in the repositroy.

[CharacterRecognition](https://github.com/cnalty/CharacterRecognition)

# Genetic Algorithms for Training Neural Nets
This repository has methods for for using genetic algorithms to train neural networks. There are a few basic mobile and arcade style games used to showcase and test. The methods have only been tested for training on fully connected layers, but have been run on convolutional layers. May work with other layers as well.

[RTGameAI](https://github.com/cnalty/RTGameAI)

# Multi-Task DDQN on Atari - with Jill Granados, Michael Stephanus, Makai Freeman
This work explred the effect of multi-task in Reinforcement Learning using the Double Deep Q-Network (DDQN) Hasselt et al developed a DDQN based on the Deep Q-Learning Network by Mnih et al. to mitigate the overestimation of values of actions in an attempt to have the network find a more general solution. We used DDQN to train a model to play Atari 2600 games either as a single task or part of a multi task process to determine how much the multi-task model will outperform the single-task and when the performance then decreases. Our findings suggest that there is little to no performance increase when training multiple tasks versus a single task with the difference becoming greater as more tasks are added.

[Analysis of Multi-Tasking Reinforcement Learning](cnalty.github.io/MTLDDQN.pdf)

