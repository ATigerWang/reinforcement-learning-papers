# Reinforcement Learning Papers  
A list of recent papers regarding reinforcement learning. I am more interesting in the research that applys reinforcement learning to game AI, so most papers listed here are focus on running experiments on games.
Some of them that I have read are marked and I will arrange some notes soon.

# Review  
  * [Deep Reinforcement Learning: An Overview](http://arxiv.org/abs/1701.07274), Li Yuxi, *arXiv*, 2017.
  * [Deep Learning for Video Game Playing](http://arxiv.org/abs/1708.07902), Justesen Niels et al., *arXiv*, 2017.
  * [Reinforcement Learning: An Introduction](http://incompleteideas.net/sutton/book/bookdraft2017nov5.pdf), Richard S. Sutton and Andrew G. Barto, 2017.


# Single Agent Reinforcement Learning   

## Value Methods  
These algorithms usually map the state to action-values and then map the action-values to the optimal action.   
  * [Playing Atari with Deep Reinforcement Learning](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf), V. Mnih et al., *NIPS Workshop*, 2013.  
  * [Human-level control through deep reinforcement learning](http://www.nature.com/nature/journal/v518/n7540/pdf/nature14236.pdf), V. Mnih et al., *Nature*, 2015.   
  * [Deep Reinforcement Learning with Double Q-learning](http://arxiv.org/abs/1509.06461), H. van Hasselt et al., *arXiv*, 2015.  
  * [Prioritized Experience Replay](http://arxiv.org/abs/1511.05952), T. Schaul et al., *ICLR*, 2016.  
  * [Massively Parallel Methods for Deep Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Publications_files/gorila.pdf), A. Nair et al., *ICML Workshop*, 2015.  
  * [Dueling Network Architectures for Deep Reinforcement Learning](http://arxiv.org/abs/1511.06581), Z. Wang et al., *arXiv*, 2015.  
  * [Deep Recurrent Q-Learning for Partially Observable MDPs](http://arxiv.org/abs/1507.06527), M. Hausknecht and P. Stone, *arXiv*, 2015.  
  * [Deep Attention Recurrent Q-Network](http://arxiv.org/abs/1512.01693), Ivan Sorokin et al., *arXiv*, 2015.  
  * [PGQ: Combining policy gradient and Q-learning](http://arxiv.org/abs/1611.01626), Brendan O'Donoghue et al., *arXiv*, 2017.  


## Policy Methods
Most of policy gradient algorithms usually need to compute the value when training, thus will be combined with value methods. And they only use policy function when test, so I classify them together as policy methods.  
  * [Asynchronous Methods for Deep Reinforcement Learning](http://arxiv.org/abs/1602.01783), V. Mnih et al., *arXiv*, 2016.  
  * [Reinforcement Learning Through Asynchronous Advantage Actor-Critic on a GPU](https://arxiv.org/abs/1611.06256), Mohammad Babaeizadeh et al., *ICLR*, 2017.  
  * [Deterministic Policy Gradient Algorithms](http://proceedings.mlr.press/v32/silver14.pdf), Silver David et al., *ICML*, 2014.  
  * [Continuous control with deep reinforcement learning](http://arxiv.org/abs/1509.02971), T. P. Lillicrap et al., *ICLR*, 2016.  
  * [Reinforcement Learning With Unsupervised Auxiliary Tasks](http://arxiv.org/abs/1611.05397),  M Jaderberg et al., *ICLR*, 2017.  
  * [High-Dimensional Continuous Control Using Generalized Advantage Estimation](http://arxiv.org/abs/1506.02438), J. Schulman et al., *ICLR*, 2016.  
  * [Sample Efficient Actor-Critic with Experience Replay](http://arxiv.org/abs/1611.01224), Wang Ziyu et al., *ICLR*, 2017.  

# Multi Agent Reinforcement Learning  
TODO: It's too ambiguous to categorize the papers below, so I will classify them again by another measure.  
## Value Methods  
 * [Multiagent Cooperation and Competition with Deep Reinforcement Learning](https://arxiv.org/pdf/1511.08779.pdf), Tampuu A et al., *arXiv*, 2015.  
 * [Opponent Modeling in Deep Reinforcement Learning](http://arxiv.org/abs/1609.05559) by He H et al., *ICML*, 2016.  
 * [Learning to Communicate with Deep Multi-agent Reinforcement Learning](https://arxiv.org/pdf/1605.06676.pdf), Foerster J et al., *NIPS*, 2016.  
 * [Stabilising Experience Replay for Deep Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1702.08887.pdf), Foerster J et al., *arXiv*, 2017.  
 * [Learning to communicate to solve riddles with deep distributed recurrent q-networks](https://arxiv.org/pdf/1602.02672.pdf), Foerster J N  et al., *arXiv*, 2016.  

## Policy Methods  
 * [Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments](https://arxiv.org/pdf/1706.02275.pdf), Lowe R et al., *arXiv*, 2017.  
 * [Learning multiagent communication with backpropagation](http://arxiv.org/abs/1605.07736), Sukhbaatar S and Fergus R, *NIPS*, 2016.  
 * [Multiagent Bidirectionally-Coordinated Nets for Learning to Play StarCraft Combat Games](https://arxiv.org/pdf/1703.10069.pdf), Peng P et al., *arXiv*, 2017.  

# Acknowledgement    
Thanks to [junhyukoh](https://github.com/junhyukoh/deep-reinforcement-learning-papers) and  [LantaoYu](https://github.com/LantaoYu/MARL-Papers). Their collection help me a lot and most information of above papers were copied from them.
