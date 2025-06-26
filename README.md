# CurrentEmergingTrendsinCS2025
Pirate Intelligent Agent – Project Reflection
Project Summary
For this project, I worked on creating a pirate intelligent agent using a Deep Q-Learning algorithm to solve a pathfinding problem. 
The goal was to train a non-player character (the pirate) to find treasure in a maze-like environment before a human player. 
I was provided with starter code that included the maze environment and experience replay buffer (TreasureMaze.py and GameExperience.py). 
My main contribution was to complete the Q-training loop in the Jupyter Notebook (Lowe_Nathanial_ProjectTwo.ipynb) by implementing the training logic for reinforcement learning, tuning hyperparameters, and ensuring the agent learns to reach the treasure consistently.

I implemented logic for:
Randomizing the agent's start location
Choosing actions via epsilon-greedy strategy
Feeding state-action-reward transitions into a neural network
Updating the Q-values via backpropagation
Tracking win history to monitor agent performance

Connection to Computer Science
Computer science is fundamentally about solving problems using algorithms, data, and computation. Through this project, I applied reinforcement learning, a key AI subfield, to teach an agent how to make decisions in a dynamic environment. 
This mirrors how computer scientists approach real-world problems—from autonomous navigation to automated trading systems.
The process involved breaking a complex problem (maze solving) into manageable components—model design, environment setup, learning algorithm, and evaluation. This modular thinking and iterative improvement is central to a computer scientist's mindset.

Ethical Considerations
As a computer scientist, I recognize the ethical responsibility to ensure that AI systems are transparent, reliable, and fair. 
Although this project was a game simulation, similar AI techniques are used in high-stakes applications like healthcare and finance. 
Ensuring models are trained responsibly, behave predictably, and respect user privacy is essential. My role includes being vigilant about bias, safety, and how decisions made by intelligent systems affect real users and organizations.
