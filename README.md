# Deep-Reinforcement-Learning-from-Human-preferences
A try of implementation of the paper Deep Reinforcement Learning from Human Preferences for proving my motivation to a EPFL lab and working with them on a semester project.

### Game rule

The player controls a yellow point in a 2D world and must reach a goal (a green point) within 25 steps. The player has four actions: up, down, left, and right, which change the x and y values of the yellow point. The player loses if he didn't reach the goal in less than 25 steps and win if the yellow point reached the green point. 


### Deep Reainforcement learning from human preference implemantation

The game is played once, and at the end, the program asks the human to choose their preference between two randomly chosen states from the game. The actions taken during the game are chosen by an actor model, but the model does not yet learn. Future commits will address this issue. The reward model learns by asking the human for their preference, but further investigation is needed to ensure that the model understands how to win the game. 


This program implement all the basic mecanism to work with a deep reinforcement learning from human preference.