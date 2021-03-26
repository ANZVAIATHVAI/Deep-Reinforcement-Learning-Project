# Deep-Reinforcement-Learning-Project (DQL)

This project is part of the Deep Reinforcement Learning course I followed on Udacity.  

Aim of the project is to *train* an agent through a Deep Reinforcement Learning technique (the Deep Q-Learning, DQL) in order to successfully *play* the game embedded in a certain Unity environment.

The environment is just a box with yellow and blue bananas lying around.  
To '*play* the game' means that the agent has 'to *act* in the environment in order to collect the highest number of rewards', that is to collect the highest number of yellow bananas.  
But the agent is not provided with any information about the rules of the game. In a first phase, it just acts (i.e. moves in any of four directions: back/forth, left/right) with no strategy. Acting, it will find out that it will be rewarded when moving through yellow bananas and penalized when moving through blue bananas. Keeeping track of 'good' moves and 'bad' moves while 'tasting' different moves, the agent will *learn* a strategy (the strategy in some way is 'taught' by the environment).  
Such phase for the agent is the **training phase** through reinforcement learning.  
The specific combination of model and algorithm adopted here to train the agent is called Deep Q-Learning, since it's mainly based on deep neural network (a supervised-learning technique), and Q-Learning (a foundational reinforcement-learning technique).

Once trained, the agent can be seen in action in the Unity environment.  
Take a look!  
<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="TrainedAgent/frame.png">
    <source src="TrainedAgent/TrainedAgent.mp4" type="video/mp4">
  </video>
</figure>

## Installation
Follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

## Execution
Open the Navigation.ipynb notebook.  
Run steps from 1 to 4 to train an agent.
Run step 5 if you want to watch the agent play. If you don't train it, a pre-trained version is available.    
