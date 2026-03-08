# ACS
# Alien Classroom Simulator

**Alien Classroom Simulator** is a 3D simulation and puzzle game developed in **Unity** where the player takes the role of a teacher responsible for training alien students to behave like humans.

The goal is to help aliens integrate into human society without being discovered by identifying suspicious behaviour, teaching social norms, and evaluating their performance.

---

# Game Overview

In this game the player manages a classroom of disguised aliens that must learn how to behave like humans.

Through a combination of **teaching mechanics**, **observation gameplay**, and **verification systems**, the player must ensure that aliens can safely blend into society.

The game focuses on:

* observation and deduction
* pattern recognition
* social behavior simulation
* light puzzle mechanics

---

# Core Gameplay Loop

1. **Classroom Training**

   * Aliens ask questions about human behaviour.
   * The player selects correct answers to teach them.

2. **Alien Detection**

   * The player observes characters in a public environment.
   * Suspicious behaviour must be identified.

3. **Border Verification**

   * Trained aliens are evaluated at an inspection checkpoint.

4. **Evaluation**

   * The system calculates the **Class Excellence Score**.

---

# Core Features

* 3D simulation gameplay
* Classroom teaching mechanic
* Alien detection gameplay
* Behaviour-based NPC AI
* Progressive difficulty system
* Stylized low-poly visual style
* Single player experience

---

# Technologies Used

| Technology   | Purpose              |
| ------------ | -------------------- |
| Unity Engine | Core game engine     |
| C#           | Gameplay programming |
| Unity URP    | Rendering pipeline   |
| Git / GitHub | Version control      |
| Blender      | 3D asset creation    |

---

# Project Structure

Example Unity project structure:

```
Assets
│
├── Scripts
│   ├── Core
│   ├── Gameplay
│   ├── AI
│   ├── UI
│
├── Prefabs
│
├── Scenes
│
├── Materials
│
├── Animations
│
└── Audio
```

---

# Core Systems

## Game Manager

Handles game states and progression.

## Quiz System

Manages classroom questions and answers.

## NPC System

Controls human and alien characters.

## Detection System

Allows the player to identify disguised aliens.

---

# Difficulty Progression

| Cycle | Questions | NPCs | Hidden Aliens |
| ----- | --------- | ---- | ------------- |
| 1     | 5         | 6    | 1             |
| 2     | 7         | 8    | 2             |
| 3     | 10        | 12   | 3             |
| 4     | 12        | 15   | 4             |
| 5     | 15        | 20   | 5             |

---

# Installation

1. Clone the repository

```
git clone https://github.com/username/alien-classroom-simulator.git
```

2. Open the project using **Unity Hub**

3. Use Unity version recommended in the project settings.

4. Open the main scene and press **Play**.

---

# Development Roadmap

Planned milestones:

Phase 1

* Core gameplay prototype
* Classroom mechanic
* Basic NPC behaviour

Phase 2

* Detection gameplay
* Environment scene
* UI system

Phase 3

* Difficulty progression
* Audio implementation
* Visual polish

Phase 4

* Steam build
* Performance optimization
* Final testing

---

# Future Features

Possible future improvements:

* more alien types
* additional environments
* advanced behaviour AI
* story campaign mode

---

# Author

Eduard Mocan

Game Design / Development

---

# License

This project is licensed under the MIT License.
