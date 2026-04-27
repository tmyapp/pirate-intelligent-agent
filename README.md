# pirate-intelligent-agent
Deep Q-learning agent that learns to navigate a maze and find a treasure using reinforcement learning (CS 370 Project Two).

### Project Overview

In this project, I built a pirate intelligent agent using deep Q-learning to solve a pathfinding problem in a maze. I was given starter code including the environment (TreasureMaze.py) and the experience replay system (GameExperience.py). My main responsibility was completing the Q-learning training loop (qtrain) and ensuring the model could learn how to navigate the maze efficiently to reach the treasure.

I implemented the training logic, including epsilon-greedy exploration, experience replay, and target network updates. I also adjusted how the model selects actions and learns from past experiences to improve performance over time. By the end of the project, the agent was able to consistently reach a 100% win rate, showing that it successfully learned the optimal path.

### Connection to Computer Science

This project helped me understand how computer scientists approach complex problems by breaking them down into smaller components and applying algorithms to learn solutions over time. Instead of hardcoding behavior, I built a system that learns from interaction, which is a core concept in artificial intelligence.

I also developed a better understanding of how to approach problems as a computer scientist. This includes testing, debugging, and iterating on solutions until the system performs correctly. Working with reinforcement learning showed me how important feedback loops and optimization are when building intelligent systems.

### Ethical Responsibilities

From an ethical standpoint, this project highlighted the importance of designing AI systems responsibly. Even though this was a simple environment, real-world AI systems can impact people directly. As a developer, I have a responsibility to ensure systems are reliable, transparent, and do not produce harmful or biased outcomes.

It’s also important to consider how AI decisions are made and whether users can trust them. In real-world applications, this means ensuring fairness, protecting user data, and avoiding over-reliance on automated systems. This project reinforced that building effective AI isn’t just about performance, but also about accountability and ethical use.
