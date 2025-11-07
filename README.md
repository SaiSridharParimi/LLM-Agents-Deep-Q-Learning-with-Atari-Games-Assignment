# LLM-Agents-Deep-Q-Learning-with-Atari-Games-Assignment

# Deep Q-Learning for Atari's Demon Attack

Implementation of Deep Q-Network (DQN) agent that learns to play Atari's Demon Attack through reinforcement learning.

## Overview

This project implements a Deep Q-Learning agent that achieves a **341% performance improvement** over baseline through systematic hyperparameter optimization:
- **Baseline:** 25 average reward, 99 steps
- **Optimized:** 110 average reward, 474 steps

## Setup Instructions

### Prerequisites
- Python 3.8+
- CUDA-capable GPU (recommended) or CPU

### Installation

1. Clone or download this repository
2. Enter `jupyter notebook` in terminal
3. Open the `atari.ipynb` file
4. Run all cells

### Code Attribution

All code implementation is original work based on:

- **DQN architecture:** Standard implementation from Mnih et al. (2015) paper "Human-level control through deep reinforcement learning"
- **PyTorch framework:** Official PyTorch documentation (https://pytorch.org/docs/)
- **Gymnasium environment:** Farama Foundation ALE/Atari (https://gymnasium.farama.org/)
- **Frame preprocessing:** Standard Atari preprocessing (grayscale conversion, resize to 84×84, normalization, frame stacking)

**No external code copied** - all implementations written from scratch based on algorithmic understanding.

**Conceptual guidance from:**
- Tutorial: Deep Reinforcement Learning for Atari Games  
  https://www.youtube.com/watch?v=hCeJeq8U0lo&feature=youtu.be
