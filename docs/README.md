* RL-glue is a collection of functions that are called by the experiment program. These functions in turn call the functions defined by the agent and environment programs. RL-glue is the glue that holds the three parts together, standardizing communication and also preventing the agent from directly communicating with the environment. 

<div align="center"><img width="65" height="75" src="https://github.com/jkren6/rl-glue/blob/master/rl-glue.jpg"/></div>


* The interface is meant to provide only the basic functionality required to run a reinforcement learning experiment. The idea is to standardize the communication between three components common to every RL experiment:

  * the agent program (learning algorithm and action selection mechanism)
  * the environment program (defines the problem, a bandit or MDP)
  * the experiment program (defines how an experiment is run and what performance measures are used)
