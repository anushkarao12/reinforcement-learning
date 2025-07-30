# Reinforcement Learning 🧠🎮

This repository contains implementations of various reinforcement learning (RL) agents using Python. The focus is on building and training agents that learn optimal policies through interaction with environments using tabular methods, linear function approximation, and neural networks (PyTorch).

It was a project assignment in the edX course "MITx: Machine Learning with Python: from Linear Models to Deep Learning".

## 📁 Project Structure

📦 reinforcement-learning/

├── agent_dqn.py # Deep Q-Network agent using PyTorch

├── agent_linear.py # Agent with linear value function approximation

├── agent_linear_pytorch.py # Linear agent implemented with PyTorch

├── agent_tabular_ql.py # Classic Q-learning (tabular) agent

├── framework.py # Training framework/environment interface

├── game.tsv # Game or environment dataset

├── utils.py # Utility functions (e.g., plotting, metrics)

├── README.md # Project overview and usage guide


## 📌 Key Features

- ✅ Implementations of various RL agents:
  - Tabular Q-Learning
  - Linear Q-Learning
  - Deep Q-Learning (DQN)
- 🧱 Modular framework for training and testing agents
- 📊 Support for training with tabular or PyTorch-based methods
- 🗂 Structured code for experimentation and expansion

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/anushkarao12/reinforcement-learning.git
   cd reinforcement-learning
   ```
2. Install dependencies
   
```
pip install -r requirements.txt
(Create one using pip freeze > requirements.txt if not available.)
```
4. Run an agent

Example:
python agent_tabular_ql.py

## 🧪 Agents

| File Name               | Description                                        |
|-------------------------|----------------------------------------------------|
| agent_tabular_ql.py     | Implements basic Q-Learning                        |
| agent_linear.py         | Linear value approximation without PyTorch         |
| agent_linear_pytorch.py | Linear agent using PyTorch for training            |
| agent_dqn.py            | Deep Q-Network (DQN) with experience replay        |

 ## 🛠 Environments

The environment appears to be based on a custom setup or task, potentially described in framework.py and game.tsv.
You can modify or extend the environment inside framework.py to suit different reinforcement learning tasks.

## 🧠 Concepts Covered

- Reinforcement Learning fundamentals (states, actions, rewards)
- Value function approximation
- Exploration vs. Exploitation (e.g., ε-greedy)
- Q-learning and Deep Q-learning
- PyTorch model training (for DQN & linear agents)

## 📌 To Do

- Add visualizations of learning curves
- Integrate OpenAI Gym environments
- Add support for policy gradient methods
- Add config file for easy hyperparameter tuning

## 📜 License

Open-source under the MIT License. Free to use, modify, and distribute.
