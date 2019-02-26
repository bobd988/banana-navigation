# Going Bananas!

### Project Details

In this project a deep neural network reinforcement learning agent learns how to navigate (and collect bananas) in a large, square world.  The square world environment is provided by Unity's open source [Machine Learning Agents (ML-Agents)](https://github.com/Unity-Technologies/ml-agents) plugin that enables games and simulations to serve as environments for training intelligent agents.      


A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the trained agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space provided by the Unity environment has 37 dimensions 

- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

Environment is considered solved when an average reward of +13 for 100 episodes is reached. 

### Getting Started

1. Download the environment from one of the links below.  You need select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
 
2. Place the file in folder and unzip the file. 

3. Start by opening a Jupyter Notebook. Open the `Navigation.ipynb` notebook to change the environment path to the above unzipped location. 
 
4. Run the notebook to train and test the environment.
 