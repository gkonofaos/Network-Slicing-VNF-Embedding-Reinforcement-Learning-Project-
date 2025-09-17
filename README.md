# Network-Slicing-VNF-Embedding-Reinforcement-Learning-Project-

## Network Slicing & VNF Embedding – Reinforcement Learning Project

### Overview

This project explores dynamic placement of Virtual Network Functions (VNFs) on cloud servers using reinforcement learning. The aim is to minimize SLA violations, node power usage, and migration costs.

The repository contains:

Phase 1 Report: MDP modeling and Policy Iteration for small-scale networks.

Phase 2 Report: Tabular Q-learning and Deep RL approaches for larger networks.

Final.ipynb: Complete Python implementation combining simulation and experiments.

```text
network-slicing-rl/
│
├── Phase1_Report.pdf      # MDP formulation, environment, Policy Iteration
├── Phase2_Report.pdf      # Q-learning, Deep RL, larger network experiments
├── Final.ipynb            # Full Python implementation
└── README.md


### Usage

Open the notebook
Launch Final.ipynb in Jupyter or Google Colab to run simulations and experiments.

Phase 1:

Implements a small network scenario as an MDP.

Uses Policy Iteration to compute optimal placement strategies.

Phase 2:

Implements Q-learning and approximate Deep RL for larger networks.

Compares performance and scalability with Phase 1 results.

### Highlights

MDP-based modeling: Defines states, actions, transitions, and cost function for VNFs on cloud nodes.

Policy Iteration: Finds optimal policies for small networks.

Q-learning / Deep RL: Handles larger networks where exact MDP methods are infeasible.

Scalability experiments: Demonstrates runtime and convergence for increasing network sizes.

### Technologies

Python 3

Libraries: NumPy, Matplotlib, Jupyter Notebook

Concepts: MDPs, Policy Iteration, Q-learning, Deep Reinforcement Learning, Network Slicing
