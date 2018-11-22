# DRLP2-Continuous-Control
Udacity Continuous Control Project  
See detailed instruction : https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control


This folder contains the different files which are necessary to make 20 agents solving Unity Double Joined Arm environment with a reward >30 after about 100 episodes.
See here under the pre requisites from Udacity to install and Test Unity Environmnent.

The files in this folders have to be installed in a single repository.
-In the Jupyter Notebook <Continuous_Control1> you find 
    -the call to the libraries
    -how to start Unity Double Join arm environment (20 agents environment) have been leveraged
    -how to call the API to interact with Unity Double Join arm environment
    -The code to train the DDPG Agent
-ddpg-agent.py : The DDPG agent whihc have been adapted from the Udacity DDPG Pendulum agent
-model.py :  The document which encode the Actor and Critic Neural Network which have been adapted from DDPG Pendulum
-The checkpoints actor and critic files where you find the Neural Network Weights
-Unity environment log

NB : Python libraries folder have not been uploaded but need to be installed in the same folder



The Environment : from Udacity P2 continuous project instruction 

Follow the instructions below to explore the environment on your own machine! You will also learn how to use the Python API to control your agent.
Step 1: Activate the Environment
If you haven't already, please follow the instructions in the DRLND GitHub repository to set up your Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

Step 2: Download the Unity Environment
For this project, you will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

Version 1: One (1) Agent
Linux: click here
Mac OSX: click here
Windows (32-bit): click here
Windows (64-bit): click here
Version 2: Twenty (20) Agents
Linux: click here
Mac OSX: click here
Windows (32-bit): click here
Windows (64-bit): click here
Then, place the file in the p2_continuous-control/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link (version 1) or this link (version 2) to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

Step 3: Explore the Environment
After you have followed the instructions above, open Continuous_Control.ipynb (located in the p2_continuous-control/ folder in the DRLND GitHub repository) and follow the instructions to learn how to use the Python API to control the agent.

Watch the (silent) video below to see what kind of output to expect from the notebook (for version 2 of the environment), if everything is working properly! Version 1 will look very similar (where you'll see a single agent, instead of 20!).
