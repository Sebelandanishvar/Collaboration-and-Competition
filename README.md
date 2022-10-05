# Collaboration-and-Competition
For this project, we will work with the Tennis environment.
[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif "Trained Agent"

### Introduction
The purpose of this project is to bounce a [Tennis ball](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis)  over a net using rackets, and each agent must keep the ball in play by manipulating the racket.

![Trained Agent][image1]

In this environment, an agent receives a reward of +0.1 if it hits the ball over the net. In the case of a ball hitting the ground or going out of bounds, an agent receives a -0.01 reward.

There are eight variables in the observation space of the game, which correspond to the ball's position and velocity as well as the racket's position. Observations are received by each agent on a local basis. In addition, two continuous actions are available, namely moving toward (or away from) the net and jumping.

For each of your agents to achieve a +0.5 average score over 100 consecutive episodes, after taking the maximum across both agents, you must solve the environment. In particular,

Every episode, we add up all the rewards each agent received (without discounting), to get an overall score. The result is two (potentially different) scores. These two scores are then added together to get the maximum score.
Each episode is then given a score.
When the average of those scores (over 100 episodes) exceeds 0.5, the environment is considered solved.


### Getting Started


1. Clone the repository git clone (https://github.com/Sebelandanishvar/Collaboration-and-Competition.git)

    To set up your Python environment, please follow the instructions in the DRLND GitHub repository (https://github.com/udacity/deep-reinforcement-learning#dependencies). PyTorch, ML-Agents, and several other Python packages are required to complete this project.

2. Please click on one of the links below to download the environment. The only thing you need to do is select the appropriate environment for your operating system:    
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

3. Unzip (or decompress) the file in the 'p3_collab-compet/folder' in the DRLND GitHub repository. 

### Instructions

Follow the instructions in `Tennis.ipynb` and feel free to get started with training your own agent!  
Enjoy it!

