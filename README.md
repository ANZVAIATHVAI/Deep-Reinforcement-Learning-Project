# Deep-Reinforcement-Learning-Project (DQL)

This project is part of the Udacity course I followed on Deep Reinforcement Learning.

The project aims to train an agent through a Deep Reinforcement Learning technique (the Deep Q-Learning, DQL) to *play* a game in a Unity environment.

The environment consists of a box with yellow and blue bananas lying around.  
To *play* the game means to the agent that it has 'to *act* in the environment in order to collect the highest reward'.  
Indeed, the agent is not provided with any information about the rules of the game. In the first phase, it just acts (i.e. moves in any of four directions: back/forth, left/right) with no strategy. Acting, it will find out that it'll be rewarded when moving through yellow bananas and penalized when moving through blue bananas. Tracking 'good' moves and 'bad' moves and 'tasting' different moves, the agent will *learn* a strategy (the strategy in some way is 'taught' by the environment).  
Such phase for the agent is the **training phase through reinforcement learning**.  
The specific combination of model and algorithm adopted here to train the agent is referred to as Deep Q-Learning, since it's mainly based on deep neural network (a supervised-learning technique), and Q-Learning (a foundational reinforcement-learning technique).

Once trained, the model can be seen in action in the Unity environment! 
Here, a video:

## Installation
Follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.
