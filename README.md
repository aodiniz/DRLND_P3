
# Udacity Deep Reinforcement Learning Nanodegree - Project 3 (Collaboration and Competition)

## Description

This project aims the develpment of a training routine for 2 agents, each controlling a racket and playing tennis one against the other.
This configuration is based on the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.
The goal is to keep the ball in play, so the final reward is common to both agents. A reward of +0.1 is given to one agent if it hits the ball over the net; otherwise, if it hits the ball out of bounds or lets the ball hit the ground, a reward of -0.01 is assigned. The final reward value for each episode is obtained by summing up all rewards of each agent separately and saving the maximum value.

The state space has 8 dimensions, comprising the position and velocity of the ball and the racket (given to each agent separately, based on its point of view).
The action space is a vector with 2 dimensions (continuous numbers between -1 and 1), for the movements to/from the net or up/down.

The task is episodic and the solution is achieved when the agents gets an average score of +0.5 for 100 consecutive episodes.

## Steps

1. Install the following python libraries:
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) (v0.4.0)
- PyTorch (v0.4.0)
- NumPy
- Matplotlib

2. The OS chosen for the development was Ubuntu, for which there are two possible environment files available for download:
- [with visual feedback](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
- [without visual feedback](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip)

3. Download and uncompress the compatible environment file.

4. Run the `Tennis.ipynb` notebook to train and evaluate the agent.

