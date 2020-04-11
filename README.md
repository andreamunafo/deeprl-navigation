# Deep RL navigation: Project details
Project to solve the Unity Banana Collector Environment using deep reinforcement learning.
The agent moves and navigates in a large, square banana world and its goal is to collect yellow bananas while avoiding blue ones. 

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

The project uses [Unity ML-Agent toolkit](https://github.com/Unity-Technologies/ml-agents)

# Getting Started
## Installing dependencies 
The file environment.yml contains the dependencies to run this project.
You can install it using Anaconda and running: `conda create --name <env> --file environment.yaml`

## How to run the code
Run the `navigation.ipynb` notebook.

