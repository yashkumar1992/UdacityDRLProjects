## Project : Reacher - Continuous Control 
Folder Name: Continuous_Control
### Project Details
Environment consists of a double-jointed arm can move to target locations.
A reward of +0.1 is provided for each step that the agent's hand is in the goal location.
#### Goal
Maintain robotic arm's position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.
#### State
The state space has 33 variables dimensions and contains the agent's position, rotation, velocity, and angular velocities.
#### Action
Four Continuous Torques Values for the Arm.
#### Reward
Robotic Arm in Goal Position => +0.1
#### Goal
An agent must get an average score of +30 over 100 consecutive episodes

#### Getting Started
Refer below to setup Udacity Project
https://github.com/udacity/deep-reinforcement-learning

Refer below to setup of the Unity Environment 
https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Readme.md

#### Instructions
Follow the instructions in `Continuous_Control.ipynb` to get started with training your own agent! 
The same notebook has a section to play with the trained agent. The code saves the trained model weights by the name "checkpoint_actor.pth","checkpoint_critic.pth"
