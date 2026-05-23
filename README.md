# Maze Navigation — Reinforcement Learning 🤖

Autonomous maze navigation agents built using Deep Q-Network 
and Actor-Critic architectures with PyTorch.

## Projects

### Project 1 — Deep Q-Network (DQN)
- 6x6 grid world with obstacles
- Q-Network with 2 hidden layers (64 units each)
- Experience replay memory (size: 1000)
- Agent learns optimal path from start to goal

### Project 2 — Actor-Critic Agent
- 5x7 grid world with static and moving obstacles
- Separate Actor and Critic neural networks (PyTorch)
- Actor: outputs action probabilities (Softmax)
- Critic: estimates state value
- Discount factor gamma=0.99

## Tech Stack
Python, PyTorch, NumPy, Matplotlib

## Key Concepts
- Deep Reinforcement Learning
- Q-Learning with Neural Networks
- Actor-Critic Architecture
- Grid World Environment Design
- Moving obstacle navigation

## How to run
pip install torch numpy matplotlib
jupyter notebook RL_project_2__suma_.ipynb
jupyter notebook RL_Project_3.ipynb
