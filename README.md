# Energy-Aware Chaser Game
### A Simple DRL Environment for Energy-Constrained Decision Making

**Author:** Tanawat Srijinda

---

## Motivation
Most control systems optimize performance only.
However, real-world systems are energy-limited.

**Key Question**
> How can an agent balance task success and energy efficiency?

---

## Core Idea
- Agent chases a moving target
- Environment: 2D Grid World
- Every action consumes energy

Goal: Reach the target using minimal energy

---

## Environment Overview
- 🔵 Agent (Controller)
- 🔴 Target (Goal)
- 🔋 Energy as a limited resource

Each movement has a cost.

---

## State and Action

**State**
