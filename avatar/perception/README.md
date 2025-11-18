# Perception Module

The Perception module provides the avatar with an understanding  
of its environment, similar to how humans observe the world.

It extracts structured information from:

- Screen content (images, UI components, positions)  
- Terminal or console output  
- File system state and metadata  
- Application responses or system feedback  

Perception outputs a normalized “world state”  
that other modules—especially Memory and Planner—rely on.

This module defines *what the avatar can see*.
