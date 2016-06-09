# RunningMinion -- CS275

## Introduction
In this project, we designed a virtural game where a Minion is running and jumping in order to survive in the harsh living environment. In the game setting, a Minion is controlled by our algorithm to run as far as possible. Along the way, the minion is running at a constant speed, and it needs to jump at an appropriate position to avoid collision with obstacles. We implemented the game in Pygame and used a reinforcement learning algorithm (Q-learning) to learn the learn a decision policy that guides the Minion to take actions at an appropriate timing. The experiments results show the superiority of our work and the learned agent could manage to survive in the cruel living environment for a long time.

## Demo page
The demo webpage with a brief description of the project is in demo/index.html.

## Code structure
Game source code: PLE/ple/games/minion  
Agent: PLE/agent.py  
Learning: PLE/minion_learning.py
To play the game: PLE/test.py
