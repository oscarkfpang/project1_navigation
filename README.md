# Project 1: Navigation
Udacity's Deep Reinforcement Learning Nanodegree Program - Project 1 Navigation


[//]: # (Image References)

[image1]: img/banana.gif "Trained Agent using Deeep Q-Network (DQN)"



### Introduction

This is the implementation of the Project 1 - Navigation. 

A Deep Q-Network RL agent is trained to collect yellow bananas in a Unity virtual environment.

This is the actual running of the DQN agent after training.
![Trained DQN Agent][image1]

### Reward and Action

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

### Installation of Environment

1. Follow the instructions of the Udacity's Deep Reinforcement Learning (DRLND) GitHub page [click here](https://github.com/udacity/deep-reinforcement-learning) for installing the OpenAI Gym and other necessary packages depending on your OS (I use Ubuntu-18)

2. Clone this repository and place it into the DRLND GitHub repository, in the `p1_navigation/` folder.

3. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

4. Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file. 

5. You will also need to install Jupyter Notebook according to the instruction here:
    - Jupyter Notebook: [click here](https://jupyter.readthedocs.io/en/latest/install.html)

### Execution

Simply run the file `Navigation.ipynb` using Jupyter notebook to get start!

### Training Outcome

The DQN agent has been trained to achieve the score of over 13.0 in 100 consecutive episodes. For more details, please refer to the `Navigation.ipynb`.
