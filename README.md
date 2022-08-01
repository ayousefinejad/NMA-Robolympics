# NMA-Robolympics

Trained a reinforcement learning agent to control the robots (.e.g hopper robot or ant robot) in order to solve a variety of Olympics-themed tasks (like 100-meter dash and marathon) 

## General Information
### Observation Space
The state space consists of positional values of the diffrent body parts of the robot, followed by velocities of those individual parts with all the positions ordered before all the velocities.


### Action Space
The agent take a 3-element vector for actions. the action space is a continuous action in range -1 to 1.
Action represents the numerical torques applied between links.


### Rewards Function
Some important rewards: 
[alive bonus + progress + electricity cost +  speed reward + jump reward]

alive bouns: Every timestep that the hopper is alive, it gets reward of 1.

progress: This reward would be positive if the hopper hops forward or right desired.

electricity cost: A negetive reward for penalizing the hopper if it take action that are too large.







## Resualt 
![alt text](https://github.com/ayousefinejad/NMA-Robolympics/blob/23efb91d976302c1e45de6b642b083175c85e4ba/Resualt_Video.gif?raw=true)
