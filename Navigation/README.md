## Project : Navigation
Folder Name: Navigation
### Project Details
Environment consists of an Agent collecting Blue/Yellow Bananas by navigating the space. The goal is to collect as many yellow bananas as possible while avoiding blue bananas.
#### State
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.
#### Action
Four Discrete Actions\
0 - move forward.\
1 - move backward.\
2 - turn left.\
3 - turn right.
#### Reward
Yellow Banana => +1\
Blue Banana => -1
#### Goal
An agent must get an average score of +13 over 100 consecutive episodes

#### Getting Started
Refer below to setup Udacity Project
https://github.com/udacity/deep-reinforcement-learning

Refer below to setup of the Unity Environment 
https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Readme.md

or

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in this  GitHub repository, in the `Navigation/` folder, and unzip (or decompress) the file. 


#### Instructions
Follow the instructions in `Navigation.ipynb` to get started with training your own agent! 
The same notebook has a section to play with the trained agent. The code saves the trained model weights by the name "model.pth"

