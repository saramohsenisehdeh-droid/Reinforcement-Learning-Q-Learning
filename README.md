# Q-Learning on Frozen Lake (Gymnasium)

This project implements a **Q-learning agent** to solve the **Frozen Lake environment** using the Gymnasium library in Python, developed for the *Computational Neuroscience* course.

The agent is trained under both **slippery (stochastic)** and **non-slippery (deterministic)** settings, and its performance is analyzed under different reward structures and ε-greedy exploration strategies. Several refinements are applied to improve learning stability, convergence speed, and overall success rate.

## Key Points

- Implemented Q-learning from scratch in Frozen Lake (8×8 grid environment)
- Compared performance in **deterministic vs stochastic** environments  
- Applied **ε-greedy policy** with different decay strategies (linear and exponential)
- Performed **reward shaping** to improve learning efficiency
- Tuned hyperparameters including learning rate, discount factor, and exploration rate
- Evaluated training and testing performance over multiple episodes
- Visualized agent behavior in both **human and ANSI rendering modes**
