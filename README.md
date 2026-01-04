# 🚚 Collaborative-Q-Trucks-Multi-Agent-Reinforcement-Learning

A fully working **multi-agent reinforcement learning (RL)** simulation built in **AnyLogic**, where multiple autonomous “trucks” collaboratively learn optimal paths in a grid-based environment using **Q-learning**.

This project demonstrates **decentralized intelligence**, **learning from experience**, and **emergent cooperative behavior** in a clean, explainable, and application-oriented way.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Why This Project Matters](#why-this-project-matters)
- [Real-World Applications](#real-world-applications)
- [What Is Reinforcement Learning?](#what-is-reinforcement-learning)
- [What Is Q-Learning?](#what-is-q-learning)
- [Exploration vs Exploitation](#exploration-vs-exploitation)
- [Multi-Agent System Design](#multi-agent-system-design)
- [Model Architecture](#model-architecture)
- [How the Model Works (Step-by-Step)](#how-the-model-works-step-by-step)
- [Learning Algorithm Details](#learning-algorithm-details)
- [Collaboration Mechanism](#collaboration-mechanism)
- [Why Agents Behave Differently](#why-agents-behave-differently)
- [How to Run the Model](#how-to-run-the-model)
- [Evaluation Metrics](#evaluation-metrics)
- [Observed Intelligent Behavior](#observed-intelligent-behavior)
- [Limitations](#limitations)
- [Future Improvements](#future-improvements)
- [Conclusion](#conclusion)

---

## 🧠 Overview

**Collaborative-Q-Trucks-Multi-Agent-Reinforcement-Learning** is an agent-based simulation where multiple autonomous agents (trucks) learn to navigate a grid world containing obstacles and a target destination.

Each agent:
- makes decisions independently,
- learns from trial and error,
- improves over time,
- and optionally shares learned knowledge with others.

No agent is pre-programmed with a path — all intelligence **emerges from learning**.

---

## ❓ Why This Project Matters

Many real-world systems involve:
- multiple agents,
- shared environments,
- incomplete information,
- no centralized controller.

Examples include autonomous vehicles, warehouse robots, and delivery fleets.

This project shows **how intelligent behavior can emerge** using simple learning rules.

---

## 🏭 Real-World Applications

This model is directly applicable to:

- Warehouse robots (Amazon-style fulfillment centers)
- Autonomous delivery trucks
- Automated Guided Vehicles (AGVs)
- Swarm robotics
- Smart traffic routing
- Drone navigation (conceptually)

---

## 🤖 What Is Reinforcement Learning?

Reinforcement Learning (RL) is a learning paradigm where an agent:

1. Observes the current state of the environment
2. Chooses an action
3. Receives a reward (positive or negative)
4. Updates its behavior to maximize long-term reward

There is **no teacher** and **no labeled data**.

---

## 📐 What Is Q-Learning?

Q-learning is a **model-free reinforcement learning algorithm**.


Which estimates:
> “How good is it to take this action in this state?”

---

### Bellman Update Equation



It learns a value function:

