# Stochastic Agent Simulation

This project models the motion of autonomous agents using a stochastic framework inspired by biological chemotaxis.  
Each agent follows a probabilistic “run-and-tumble” behavior influenced by environmental gradients, demonstrating how random motion can still yield directed, purposeful movement.

Originally developed as part of **UC Berkeley’s MSSE (Molecular Science and Software Engineering)** program.

---

## Overview
This simulation captures how biased random walks — like those seen in *E. coli* — can emerge from simple probabilistic rules.  
The system uses Monte Carlo-style updates to simulate agent motion and visualize trajectory dynamics over time.

### Key Features
- **Stochastic Modeling:** Probabilistic motion and direction updates per agent  
- **Chemotactic Bias:** Agents respond to simulated nutrient gradients  
- **Monte Carlo Sampling:** Used to generate random step sizes and orientation changes  
- **Visualization:** Animated agent trajectories and spatial distributions over time  

---

## Files
| File | Description |
|------|--------------|
| `agent_motion_simulation.py` | Main driver script running the agent-based stochastic simulation |
| `stochastic_agent_dynamics.py` | Helper functions and motion dynamics calculations |

---

## Learning Objectives
- Implement **stochastic simulation frameworks** for biological or agent-based systems  
- Use **Monte Carlo and probabilistic modeling** to represent randomness in physical motion  
- Visualize time-dependent trajectories and emergent collective behaviors  

---

## Technologies
- Python
- NumPy
- Matplotlib
- Random Sampling
- Agent-Based Simulation

---

## Purpose
This project highlights how random processes can lead to structured outcomes — a principle that connects **statistical physics**, **biological modeling**, and **machine learning-style agent dynamics**.  
It serves as an example of how simulation techniques can model emergent, data-driven systems.

---

### Author
Developed by **Sibhi Sakthivel** as part of UC Berkeley MSSE coursework (Team 3 — *Natalia Rivera, Joseph Gill, Andy Ho, Nathalie Murphy, Sibhi Sakthivel, Yashesha Kothari*).
