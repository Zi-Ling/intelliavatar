# Planner Module

The Planner determines *how* the avatar should achieve a given goal.

Based on:

- The user’s intent  
- The current state (Perception)  
- Historical experience (Memory)  
- Available Skills and primitive Actions  

The Planner generates a coherent, multi-step strategy.

Responsibilities include:

- Decomposing goals into ordered steps  
- Selecting appropriate skills or atomic actions  
- Adjusting plans dynamically based on feedback  

This module is the avatar’s decision-making core.
