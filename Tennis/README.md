## Project : Tennis
Folder Name: Tennis
### Project Details
Environment consists of an Agents trying to control ball over the net mimicket the tennis racket game.       
#### State
The state space has 8 dimensions corresponding to the position and velocity of the ball and racket
#### Actions
Two Continuous Actions. 
1.Towards/Away. 
2.Jumping Up/Down. 
#### Reward
Each Agent:
1. Ball over the net, => +0.1.
2. Ball hit the ground or hits the ball out of bounds => -0.1. \
Final Reward=> Maximum of Score from Each Agent. 
#### Goal
An agent must get an average score of +0.5 over 100 consecutive episodes

#### Getting Started
Refer below to setup Udacity Project
https://github.com/udacity/deep-reinforcement-learning

Refer below to setup of the Unity Environment 
https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Readme.md

#### Instructions
Follow the instructions in `Tennis.ipynb` to get started with training your own agent! 
The same notebook has a section to play with the trained agent. The code saves the trained model weights by the name "checkpoint_actor.pth","checkpoint_critic.pth"
