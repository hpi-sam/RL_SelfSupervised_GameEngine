# RL_SelfSupervised_GameEngine
### Motivation
Self-adaption is a desired feature of real-time systems like flight control and driverless vehicles. Self-adaption in these systems is particularly challenging in the real world because these systems are subject to unpredictable changes that can be endogenous (e.g., partial failures or performance degradation) and exogenous (e.g., environmental or other concurrent systems). The current solution has been to trained these self-adaptation mechanism on supervised way, which implies the strong assumption that all change situations are known at training time. For this reason, the solution is to rely on simulators to produce change situations that could be used to train the adaptation mechanism in real time (continuous learning).

### Problem 
However, designing simulators is a domain-dependent task, which is difficult to generalize across domains. Recent research on game showed that it is possible to train without human input while playing the game. While this is step to continuous learning, it does not deal with two major problems: (1) how to learn when the environment is changing (e.g., changes in the game rules) and (2) when to trigger learning (how to know which events and magnitude of effects to monitor?).

### Approach 
We are interested in exploring reinforcement learning techniques to continuously train an adaptation mechanims in a self-supervised way. The adaptation mechanism is part of an agent that interacts (makes decisions) by means of actions on an environment (system) that is subject to endogenous and exogenous changes. Our insight is to model the problem as simulation architecture that is executed in run time with the deployed system. As a proof of concept, we would execute experiments both with game engine and an e-commerce engine. 

### Preliminary References
- Ameneyro, V., et al., "Playing Carcassonne with Monte Carlo Tree Search." arXiv e-prints (2020): arXiv-2009. (https://arxiv.org/pdf/2009.12974.pdf)
- Heyden, C. (2009). Implementing a computer player for Carcassonne. Master's thesis, Department of Knowledge Engineering, Maastricht University. (https://project.dke.maastrichtuniversity.nl/games/files/msc/MasterThesisCarcassonne.pdf)
- Silver, D., et al. "Mastering the game of go without human knowledge." nature 550.7676 (2017): 354-359. (https://www.nature.com/articles/nature24270.%20)
- Schrittwieser, J., Silver, D., et al, (2020). Mastering atari, go, chess and shogi by planning with a learned model. Nature, 588(7839), 604-609. (https://www.nature.com/articles/s41586-020-03051-4)

### Sequential Decision Making Techniques
- Model-Based Reinforcement Learning (DQN)
- Multi-Armed Bandits (Bayesian Bandits)
- Monte Carlo Tree Search (MCTS)
- Machine Learning on Graphs (Graph Neural Nets, Causal Inference)

### Our Sister Projects
- Reinforcement Learning for Self-Repair Mechanisms (https://github.com/hpi-sam/rl-4-self-repair)
- Multi-Armed Bandits for Self-Repair Mechanisms (https://github.com/hpi-sam/bandits-4-self-repair)

### Our Lectures
- Markov Models (https://github.com/hpi-sam/MarkovModels_Lecture)
- Graph Neural Networks (https://github.com/hpi-sam/GNN-Lecture)
- Reinforcement Learning (https://github.com/christianadriano/RL_4_SelfHealingSystems)

### get in touch with us:
- Tibor (https://github.com/tiborboglar)
- Christian (https://github.com/christianadriano)
