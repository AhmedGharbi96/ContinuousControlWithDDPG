# Learning Algorithm
We used the [DDPG](https://arxiv.org/pdf/1509.02971.pdf) algorithm to solve the 1 agent version of the Reacher environment.
The notebook contains contains 2 main parts, in the first section we initialize the environment and explore the action space, observation space and information about
the environment. In the second part, we find the implementation. The second part is composed of:
1. Actor and critic models
2. DDPG agent
3. The training loop
# Neural Network Architectures
## Actor Neural Network
* Input layer having the size of the observation space
* A fully connected layer with 400 units
* A second fully connected layer with 300 units
* Output layer having the size of the action space

## Critic Neural Network
* Input layer having the size of the observation space
* A fully connected layer with 400 units
* A second fully connected layer with 300 units
* Output layer with 1 unit
# Plots
The agent has successfully solved the environment after 178 episodes.
```
Episode 1	Average Score: 0.00
Episode 2	Average Score: 0.00
Episode 3	Average Score: 0.00
Episode 4	Average Score: 0.04
Episode 5	Average Score: 0.07
Episode 6	Average Score: 0.08
...
Episode 177	Average Score: 29.83
Episode 178	Average Score: 30.23
Enviroment solved in @ i_episode=178, w/ avg_score=30.23

```
![average score](https://github.com/AhmedGharbi96/ContinuousControlWithDDPG/blob/main/DDPG_DRLN.png)

## Potential Improvements
I would like to implement Distributed link[Distributional Deterministic Policy Gradients (D4PG] (https://arxiv.org/abs/1804.08617) algorithm and use it to solve
the 20 agents version of the environment.
