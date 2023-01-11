# Awesome Safe MARL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A (very subjective) curated list of Safe Multi-agent
Reinforcement Learning resources.


## Preliminaries

### Constrained Optimization

TODO


### Control Theory

TODO


### MBRL

TODO


### Safe RL

- [Constrained Policy Optimization](https://arxiv.org/abs/1705.10528), Achiam et al, 2017. Algorithm: CPO.

- [Saute RL: Almost Surely Safe Reinforcement Learning Using State Augmentation](https://arxiv.org/abs/2202.06558), Sootla et al, 2022. Algorithm: Saute MDP augmentation.



### Graph Theory

TODO

### Federated Learning

TODO

<!-- ## Building Blocks

TODO

## Safe MARL -->

## MARL

### Books

- Part V of [Algorithms for Decision Making](https://algorithmsbook.com/) by 
Mykel J. Kochenderfer, Tim A. Wheeler and Kyle H. Wray
- [Multiagent Systems: Algorithmic, Game-Theoretic, and Logical Foundations](http://www.masfoundations.org/index.html) by Yoav Shoham and Kevin Leyton-Brown
- [Multi-Agent Coordination: A Reinforcement Learning Approach](https://www.wiley.com/en-us/Multi+Agent+Coordination:+A+Reinforcement+Learning+Approach-p-9781119699033) by Arup 
Kumar Sadhu and Amit Konar :dollar:
- [Distributed Optimization-Based Control of Multi-Agent Networks in Complex Environments](https://link.springer.com/book/10.1007/978-3-319-19072-3) by Minghui Zhu and Sonia Martinez :dollar:


### Papers (survey)

- [Multi-agent Reinforcement Learning: An Overview](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=8851953ef486615fce803bda2e40aec97cbb5547), Busoniu et al, 2010.
- [Multi-agent deep reinforcement learning: a survey](https://link.springer.com/content/pdf/10.1007/s10462-021-09996-w.pdf), Sven Gronauer and Klaus Diepold, 2021.
- [A Survey of Multi-Agent Reinforcement Learning with Communication](https://arxiv.org/abs/2203.08975), Zhu et al, 2022.



### Papers (research)

#### POMDP for Multiple Agents

TODO


#### Value Factorization

- [Multiagent Cooperation and Competition with Deep Reinforcement Learning](https://arxiv.org/abs/1511.08779), Tampuu et al, 2015.
- [Value-Decomposition Networks For Cooperative Multi-Agent Learning](https://arxiv.org/abs/1706.05296), Sunehag et al, 2017.
- [QMIX: Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1803.11485), Rashid et al, 2018. Algorithm: QMIX.
- [QTRAN: Learning to Factorize with Transformation for Cooperative Multi-Agent Reinforcement Learning](https://proceedings.mlr.press/v97/son19a.html), Son et al, 2019.
- [QPLEX: Duplex Dueling Multi-Agent Q-Learning](https://arxiv.org/abs/2008.01062), Wang et al, 2020.


#### Policy Gradient

- [Counterfactual Multi-Agent Policy Gradients](https://ojs.aaai.org/index.php/AAAI/article/view/11794), Foerster et al, 2018.
- [Distributed Multi-Agent Reinforcement Learning by Actor-Critic Method](https://www.sciencedirect.com/science/article/pii/S240589631932035X), P. Heredia, S. Mou, 2019.




#### Communication

- [Learning to Communicate with Deep Multi-Agent Reinforcement Learning](https://proceedings.neurips.cc/paper/2016/hash/c7635bfd99248a2cdef8249ef7bfbef4-Abstract.html), Foerster et al, 2016.
- [Learning Multiagent Communication with Backpropagation](https://proceedings.neurips.cc/paper/2016/hash/55b1927fdafef39c48e5b73b5d61ea60-Abstract.html), Sukhbaatar et al, 2016.
- [TarMAC: Targeted Multi-Agent Communication](https://proceedings.mlr.press/v97/das19a.html), Das et al, 2019.
- [Learning to Ground Multi-Agent Communication with Autoencoders](https://proceedings.neurips.cc/paper/2021/hash/80fee67c8a4c4989bf8a580b4bbb0cd2-Abstract.html), Lin et al, 2021.
- [Differentially Private and Communication Efficient Collaborative Learning](https://ojs.aaai.org/index.php/AAAI/article/view/16887), Ding et al, 2021.




#### DLQR

- [Distributed Q-Learning for Dynamically Decoupled Systems](https://arxiv.org/abs/1809.08745), Siavash Alemzadeh, Mehran Mesbahi, 2018.
- [D3PI: Data-Driven Distributed Policy Iteration for Homogeneous Interconnected Systems](https://arxiv.org/abs/2103.11572), Alemzadeh et al, 2021.
- [Data-Driven Distributed Optimal Consensus Control for Unknown Multiagent Systems With Input-Delay](https://ieeexplore.ieee.org/document/8334323), Zhang et al, 2018.
- [Distributed Q-Learning with State Tracking for Multi-agent Networked Control](https://arxiv.org/abs/2012.12383), Wang et al, 2020.
- [Distributed Adaptive Linear Quadratic Control using Distributed Reinforcement Learning](https://www.sciencedirect.com/science/article/pii/S2405896319307748), Daniel Goerges, 2019.
- [Distributed Linear-Quadratic Control with Graph Neural Networks](https://arxiv.org/abs/2103.08417), Fernando Gama, Somayeh Sojoudi, 2021.
- [Distributed Online Linear Quadratic Control for Linear Time-invariant Systems](https://arxiv.org/abs/2009.13749), Ting-Jui Chang, Shahin Shahrampour, 2020.
- [Learning Distributed Stabilizing Controllers for Multi-Agent Systems](https://arxiv.org/abs/2009.13749), Jing et al, 2021. 


#### Vehicle Platoon

- [Distributed Nonlinear Model Predictive Control for Connected Autonomous Electric Vehicles Platoon with Distance-Dependent Air Drag Formulation](https://www.mdpi.com/1996-1073/14/16/5122), Caiazzo et al, 2021.



## Engineering

### Building Multi-agent Environments

- [Multi-Agent Learning Environments](https://agents.inf.ed.ac.uk/blog/multiagent-learning-environments/), blog post by Lukas Schäfer
- [PettingZoo Neurips'21 paper](https://proceedings.neurips.cc/paper/2021/hash/7ed2d3454c5eea71148b11d0c25104ff-Abstract.html)
- [PettingZoo Documentation](https://pettingzoo.farama.org/)
- [ma-gym](https://github.com/koulanurag/ma-gym) with [minimal-marl](https://github.com/koulanurag/minimal-marl), set of baselines for vanilla MARL problems by Anurag Koul
- [Ray Multi-Agent and Hierarchical Environments](https://docs.ray.io/en/latest/rllib/rllib-env.html#multi-agent-and-hierarchical)


## Related awesome lists
- [Awesome MARL](https://github.com/instadeepai/awesome-marl)
