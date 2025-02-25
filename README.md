# Flappy Bird Deep Q-Learning Agent

This repository contains the Jupyter Notebook for training and evaluating a **Deep Q-Learning (DQN)** agent to play the **Flappy Bird** game.

Youtube video link：https://youtu.be/uA6iLdWU7fM

## Description

The notebook includes:

- **Implementation of Deep Q-Learning (DQN)** for decision-making in the Flappy Bird game.
- Step-by-step instructions for setting up the agent's training environment.
- Detailed explanations of the algorithms used (DQN, Double DQN, Dueling DQN) and their applications to the problem.
- Model evaluation, visualizations of rewards, and sound effects integration.

## Methods Used

The notebook implements the following techniques and methods:

- **Q-Learning**: Basic Q-learning for the agent to learn optimal actions based on rewards.
- **Deep Q-Network (DQN)**: A neural network used to approximate the Q-values for decision-making.
- **Double DQN**: An enhancement to reduce Q-value overestimation by using two networks (one for action selection and another for Q-value evaluation).
- **Dueling DQN**: Splits the estimation of state values and action advantages, improving decision-making efficiency.
- **Experience Replay**: Stores and samples experiences randomly to improve training efficiency.
- **Sound Effects**: Integrated sound effects (jump, point, hit, die) using **pygame** to enhance training experience.

## Requirements

To run the notebook, the following dependencies must be installed:

- Python 3.x
- Jupyter Notebook
- gymnasium
- flappy_bird_gymnasium
- torch
- pygame
- matplotlib
- numpy
- yaml
