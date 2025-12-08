# Reinforcement Simple Problems

1. Classic Control Problems

### CartPole

### MountainCar
### Lunar Lander

This problem represents an optimization problem, where the engine is either full on or turned of (Pontryagin's maximum principle). The rockets trajectory should be optimized such that the rocket lands at the landing area (0,0). Environment is either discrete or continuous. The amount of fuel is not restricted, which is beneficial for learning.


Beginner Datasets & Environments
   
For Vision-Based RL:

Atari Games (via Arcade Learning Environment)

Pong, Breakout - classic starting points
Pixel-based observations, discrete actions
Well-documented, many tutorial implementations available



For Robotics:

PyBullet environments - free physics simulation

Simpler than full robotics, but more realistic than CartPole
Good middle ground



For Multi-Agent (since you're interested in agents):

PettingZoo - multi-agent version of Gymnasium

Start with simple cooperative/competitive games
