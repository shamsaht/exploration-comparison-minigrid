# Exploration Strategy Comparison in MiniGrid

This repository presents a comparative study between ε-greedy and Ensemble Metric-based Exploration (EME) strategies in reinforcement learning, applied to MiniGrid environments of varying sizes.

## Overview

Exploration is essential in sparse-reward environments like MiniGrid. This project compares:
- ε-greedy: a commonly used undirected exploration method.
- EME: a directed exploration strategy that uses an intrinsic exploration bonus based on ensemble disagreement.

The agents are evaluated on:
- 4×4 grid (simple)
- 6×6 grid (moderate)
- 8×8 grid (complex)

## Metrics Evaluated

- Success Rate
- Episode Length
- Cumulative Reward
- Exploration Bonus (EME only)

## Key Insights

- ε-greedy converges quickly in simple environments, but may struggle in complex ones.
- EME provides more consistent performance as environment complexity increases.
- Larger ensemble sizes improve exploration coverage but may slow early convergence.

## Installation

1. Clone the repository:
```bash
git clone git@github.com:shamsaht/exploration-comparison-minigrid.git
cd exploration-comparison-minigrid
```
## Project Info

This is a group project submitted for the course **ML702** at **Mohamed Bin Zayed University of Artificial Intelligence (MBZUAI)**.

## Contributors

- [Shamsa Hamad](https://github.com/shamsaht)
- Maryam Al Shamsi 
- Shaikha Al Hosani
