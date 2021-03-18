# ContinuousControlWithDDPG

## Introduction
This is the second project of the Deep Reinforcement Learning Nanodegree of Udacity.
In this environment, a double-jointed arm was trained for moving to target locations, in the Reacher environment.

![alt-text](https://github.com/AhmedGharbi96/ContinuousControlWithDDPG/blob/main/reacher.gif)

A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.
To solve this episodic task, the agent must get an average score of +30 over 100 consecutive episodes.

## Getting Started
1. Install the necessary packages. 
   Start by creating a conda environment.

```
conda create --name env_name python=3.6
```
2. Install the following packages
 ```
pip install pytorch pytorch
pip install unityagents
pip install mlagents
pip install numpy
pip install matplotlib
```
Download the Reacher unity environment You can download the environment form one of the links below. Select the enviornment that matches your OS
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
3. Clone this repository

## Running the code
After all packages have been installed in the environment you should open Jupyter Notebook using Anaconda, find and open Continuous_Control.iypnb. To run the cells you can simply click on the first one and press Shift + Enter. This can be made through the whole Notebook.
