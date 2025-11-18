# Intent Module

The Intent module is responsible for transforming raw user input  
(natural language instructions, voice commands, or structured signals)  
into a clear and actionable task specification.

Its main responsibilities include:

- Interpreting the user’s goal  
- Structuring the intent into machine-readable fields  
- Identifying constraints, target applications, and expected outcomes  
- Passing the task representation to the Planner for next-step reasoning  

This module is the "entry point" of the cognitive pipeline.  
It defines *what the avatar should do* before figuring out *how to do it*.
