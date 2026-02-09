# Energy-Aware Chaser Game
### A Simple DRL Environment for Energy-Constrained Decision Making

**Author:** Tanawat Srijinda

---

## Motivation
Most control systems optimize performance only.
However, real-world systems are energy-limited.

**Key Question**
How can an agent balance task success and energy efficiency?


---


## Core Idea
- Agent chases a moving target
- Environment: 2D Grid World
- Every action consumes energy

Goal: Reach the target using minimal energy


---


## Environment Overview
## Environment Overview

![Energy-Aware Chaser Environment](diagrams/Gemini_Generated_Image_8pniz08pniz08pni.png)

- 🔵 Agent (Controller)
- 🔴 Target (Goal)
- 🔋 Energy as a limited resource

Each movement has a cost.


---


## State and Action

![Energy-Aware Chaser Environment](diagrams/Gemini_Generated_Image_wdmvpvwdmvpvwdmv.png)

**State**

**Actions**
- Up / Down / Left / Right
- Stay (save energy)


---


## Reward Function
- +10  Reach target
- −0.1 Each step
- −λE  Energy consumption
- −5  Energy depleted

Reward defines good behavior, not rules.


---


## Learning Process
- Deep Reinforcement Learning
- No predefined rules
- Trial-and-error learning

Policy emerges automatically.


---


## Learned Behavior
- Avoids random motion
- Balances speed and energy
- Intelligent decision-making


---


## Real-World Relevance
- Robot motion planning
- Energy-aware control
- Smart factory / automation


---


## Conclusion
Simple environment  
Clear reward design  
Energy-aware intelligent control

