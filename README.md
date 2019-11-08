# Deep-RL-Navigation
## Introduction
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

## The Environment
In this project, we train Deep Q-Learning (DQN) Agent which walks around in the banana catching game simulator
(Unity ML-Agents environment). It is the first project of the [Deep Reinforcement Learning Nanodegree (DRLND)](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)
and was adapted from the original version on [Udacity Github Repository](https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation).


![image](https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* ```0``` - move forward.
* ```1``` - move backward.
* ```2``` - turn left.
* ```3``` - turn right.</br>

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

## Setup

### Step 1: Clone the DRLND Repository
Please follow the [instructions in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)
to set up your Python environment. 
These instructions can be found in ```README.md``` at the root of the repository. 
By following these instructions, you will install PyTorch, the ML-Agents toolkit, 
and a few more Python packages required to complete the project.</br>

(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

### Step 2: Download the Unity Environment
You need only select the environment that matches your operating system:</br>

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)</br>
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)</br>
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)</br>
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)</br>
Then, place the file in the p1_navigation/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.</br>

## Instructions
To train the agent, start jupyter notebook, open ```Navigation.ipynb``` and execute! 
For more information, please check instructions inside the notebook.
