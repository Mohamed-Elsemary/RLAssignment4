# RL Assignment 4: Continuous Control (SAC, PPO, TD3)

**CMPS458: Reinforcement Learning (Fall 2025)** **Computer Engineering Department - Cairo University**

This repository contains implementations of State-of-the-Art (SOTA) model-free Reinforcement Learning algorithms for continuous action-space environments. The goal is to train agents using PyTorch and publish the results to the Hugging Face RL leaderboard.

## 📌 Assignment Overview

[cite_start]The objective of this assignment is to solve **continuous control** problems using three specific algorithms[cite: 4, 9]:
1.  **SAC** (Soft Actor-Critic)
2.  **PPO** (Proximal Policy Optimization)
3.  **TD3** (Twin Delayed DDPG)

### Environments
[cite_start]The agents are trained on the following Gymnasium Box2D environments[cite: 11, 12, 13]:
* `LunarLander-v3` (`continuous=True`)
* `CarRacing-v3` (`continuous=True`)

## 📂 Repository Structure

Based on the current development branch:

* **`LunarPPO/`**: Implementation of the PPO agent specifically tuned for the continuous LunarLander environment.
* **`LunarSAC/`**: Implementation of the SAC agent.
* **`TD3 LUNAR and SAC.ipynb`**: Jupyter Notebook containing the training logic and experiments for TD3 and SAC models.

## 🛠️ Dependencies & Installation

[cite_start]To run the codes, you need to install the following Python libraries[cite: 7, 8]:

```bash
pip install gymnasium[box2d] torch wandb huggingface_hub
