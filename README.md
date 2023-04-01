# RL-flappy-bird

This Github repository contains the code implementation of the Reinforcement Learning Individual assignment relative to the 3MD3220 course.

The main purpose of this project is to implement a reinforcement learning agent capable of playing the Flappy Bird game.

We implemented two agents, each utilizing a different technique :
- Q-Learning
- Expected SARSA

Both these implementations can be found in the notebook `Individual assignment implementation.ipynb`.

A video of the trained Expected SARSA agent can be found as well under the name `Flappy Bird Gameplay.mov`.

To optimize the agents, we did a grid search on a space of parameters ($\epsilon$, $\gamma$, $\alpha$, i_lim). The results of the grid search can be found in the .csv files in the folder `results`.
