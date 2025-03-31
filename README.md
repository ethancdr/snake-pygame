![image](https://github.com/user-attachments/assets/5658ccad-df0e-45f7-bd36-887b464c5f7c)
![image](https://github.com/user-attachments/assets/a08ab027-5050-433e-8b56-e33882e0ed0a)

# Snake Game AI

A reinforcement learning project where an AI agent learns to play the classic Snake game using Q-learning. This project uses [Pygame](https://www.pygame.org/) for the game interface and [PyTorch](https://pytorch.org/) to build and train a neural network model.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

---

## Overview

This project implements the classic Snake game where an AI agent learns to play by interacting with the game environment. The agent uses Q-learning and a simple neural network model to decide its moves. Over time, it improves by training on both short-term and long-term memory of its game experience. The game is built using Pygame, and the AI is implemented in PyTorch.

---

## Features

- **Snake Game:** A fully functional Snake game implemented with Pygame.
- **AI Agent:** Reinforcement learning agent that uses Q-learning for decision making.
- **Neural Network:** A simple feedforward neural network implemented in PyTorch for approximating Q-values.
- **Visualization:** Live plotting of scores to monitor training progress using Matplotlib.
- **Modular Code:** Organized into separate modules for the game, AI model, training process, and helper functions.

---

## Installation

### Prerequisites

- Python 3.7 or higher
- pip

### Dependencies

Install the required packages using pip:

```bash
pip install pygame torch matplotlib ipython numpy
```
## Usage

### 1. Clone the Repository

Clone the repository to your local machine by running:

```bash
git clone https://github.com/your-username/snake-game-ai.git
cd snake-game-ai
```

## Running the Game and Training

To start the game and begin training the AI agent, run the main script:

```bash
python agent.py
```

## Project Structure

```plaintext
snake-game-ai/
├── game.py          # Contains the Snake game implementation using Pygame.
├── model.py         # Defines the neural network (Linear_QNet) and its trainer (QTrainer).
├── agent.py         # Implements the AI agent that interacts with the game.
├── helper.py        # Contains helper functions, including plotting utilities.
└── README.md        # This file.
