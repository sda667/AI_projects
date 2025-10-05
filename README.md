# AI Projects 

This repository collects all my AI related projects.  
Each project includes code, experiments, results, and a report.

---

## Summary Table

| Project | Topic | Reports |
|---|---|---|
| [Reinforcement Learning (RL)](https://github.com/sda667/Reinforcement_Learning) | Value Iteration (model-based) vs Q-Learning (model-free); ε-greedy & Softmax exploration | [PDF Report](https://github.com/sda667/Reinforcement_Learning/blob/main/Reinforcement_Learning_english.pdf) |
| [Neural Networks — Fashion MNIST](https://github.com/sda667/Neural_Networks) | MLP vs CNN; accuracy/loss curves; confusion matrices | [PDF Report](https://github.com/sda667/Neural_Networks/blob/main/Fashion_MNIST_English.pdf) |
| [Bayesian Network](https://github.com/sda667/Bayesian_Network) | Likelihood-based inference on a grid; belief updates; convergence | [PDF Report](https://github.com/sda667/Bayesian_Network/blob/main/bayesian_network_report.pdf) |
| [2D Ecosystem — Agent-Based Simulation](https://github.com/sda667/2D_Ecosystem) | Agent-based marine simulation; A* pathfinding; pursuit/avoidance navigation | [PDF Report(french)](https://github.com/sda667/2D_Ecosystem/blob/main/RapportScientifique_INFOF308.pdf) |


---

## Skills Highlighted

**Skills:** Reinforcement Learning (Value Iteration, Q-Learning) • Exploration strategies (ε-greedy, Softmax) • Neural network training (MLP, CNN, ReLU, Softmax, Adam) • Metric tracking (accuracy/loss curves, confusion matrices) • Bayesian inference (enumeration, likelihood design) • Results analysis and visualization.

---

## Projects

### 1. [Reinforcement Learning (RL)](https://github.com/sda667/Reinforcement_Learning)
Agent in a **7×7 maze** with step penalty and two exits (10 / 100).  
Compares **Value Iteration** (Bellman backups) vs **Q-Learning** (experience-based) under **ε-greedy** and **Softmax** exploration, and studies the effect of environment randomness \(p\).

### Highlights
- Value Iteration converges quickly and is robust to randomness.
- Q-Learning adapts to stochastic transitions but needs more episodes.

### Results
Higher long-run returns with decaying ε; well-chosen τ balances exploration/exploitation.


**Report:** [PDF](https://github.com/sda667/Reinforcement_Learning/blob/main/Reinforcement_Learning_english.pdf)

---

### 2. [Neural Networks — Fashion MNIST](https://github.com/sda667/Neural_Networks)
**MLP** vs **CNN** on Fashion-MNIST (70k images, 10 classes).  
Tracks training/validation accuracy and loss; analyzes confusion matrices and error modes.

### Highlights
- CNN achieves higher validation accuracy and better generalization.
- MLP is simpler/faster to train but shows slight overfitting.

### Results
Accuracy/loss tracked over epochs; confusion matrices summarize error patterns.

**Report:** [PDF](https://github.com/sda667/Neural_Networks/blob/main/Fashion_MNIST_English.pdf)

---

### 3. [Bayesian Network](https://github.com/sda667/Bayesian_Network)
Locate hidden gems on a grid from distance observations using **enumeration-based Bayesian inference**.  
Likelihood decreases exponentially with distance ; beliefs are normalized after each update and converge toward true positions.

### Highlights
- Exact enumeration gives interpretable posteriors on small/medium grids.
- Beliefs converge from near-uniform to peaks at true locations.

### Results
Belief updates after each observation steadily refine the posterior over positions.

**Report:** [PDF](https://github.com/sda667/Bayesian_Network/blob/main/bayesian_network_report.pdf)

---

## 4) [2D Ecosystem — Agent-Based Simulation (Applied AI)](https://github.com/sda667/2D_Ecosystem)

### Overview
2D marine ecosystem simulation with agent-based entities (fish, sharks, orcas) evolving in a dynamic environment.

### Highlights
- Agents navigate with **A\*** pathfinding for pursuit/avoidance.
- Discrete-time updates; 2D spatial model; MVC-style code structure. 
- Ecological rules: predation, competition, reproduction, plankton-driven resources.

### Results
Qualitative scenarios demonstrating extinction, stable ecosystems, and emergent schooling/predator behavior. 

### Links
- **Report (PDF):** [PDF(french)](https://github.com/sda667/2D_Ecosystem/blob/main/RapportScientifique_INFOF308.pdf)
