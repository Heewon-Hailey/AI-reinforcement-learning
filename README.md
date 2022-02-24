# Implementation of reinforcement learning algorithms in Pacman

## About the project

This work aims to understand Markov Decision Processes(MDPs) by implementing reinforcement learning algorithms and some advanced concepts. 
MDPs can address most of the Reinforcement Learning (RL) problems, and thus it is popular in Artificial Intelligence (AI) for modelling sequential decision making.

It relates to the tasks at https://berkeleyai.github.io/cs188-website/project3.html.<br>
To find full description about tasks, click the link above.
<br>

## Implementated algorithms

1. Value Iteration <br>
  `class ValueIterationAgent` in `valueIterationAgents.py`
  
2. Bridge Crossing Analysis <br>
  `def question2` in `analysis.py`

3. Policies <br>
  a) Prefer the close exit (+1), risking the cliff (-10) <br>
  b) Prefer the close exit (+1), but avoiding the cliff (-10) <br>
  c) Prefer the distant exit (+10), risking the cliff (-10) <br>
  d) Prefer the distant exit (+10), avoiding the cliff (-10) <br>
  e) Avoid both exits and the cliff (so an episode should never terminate) <br>
  `def question3a-3e` in `analysis.py`
  
4. Asynchronous Value Iteration <br>
  `class AsynchronousValueIterationAgent` in `valueIterationAgents.py`
  
5. Prioritized Sweeping Value Iteration <br>
  `class PrioritizedSweepingValueIterationAgent` in `valueIterationAgents.py`
  
6. Q-Learning <br>
  `class QLearningAgent` in `qlearningAgents.py`
  
7. Epsilon Greedy <br>
  `def getAction` in `class QLearningAgent` in `qlearningAgents.py`
  
8. Bridge Crossing Revisited <br>
  `def question8` in `analysis.py`
  
9. Q-Learning and Pacman <br>
  `class PacmanQAgent` in `qlearningAgents.py`
  
10. Approximate Q-Learning <br>
  `class ApproximateQAgent` in `qlearningAgents.py`
<br>

## How to run

For test:<br>
`Run the command: python autograder.py`
<br>

----

This project is part of individual projects from COMP90054 AI Planning for Autonomy in School of Computing and Information Systems, The University of Melbourne. 


