# Math-AI-Engine

This project builds an AI system capable of solving mathematics,
physics, and aeronautical engineering problems.

The system uses the DeepSeek Math model with structured reasoning.

Features

- step-by-step reasoning
- symbolic mathematics solving
- physics equation solving
- runs on Kaggle GPU

Model

deepseek-ai/deepseek-math-7b-instruct

Hardware

Kaggle T4 GPU


## Example Problems

### Example 1 — Algebra

Problem:

Solve the quadratic equation:

x² − 5x + 6 = 0

Expected Output:

x = 2, x = 3


### Example 2 — Aeronautical Engineering

Problem:

Air flows over a wing with velocity 120 m/s.  
Air density = 1.225 kg/m³  
Wing area = 25 m²  
Lift coefficient = 0.8  

Compute the lift force.

Formula:

L = ½ ρ V² S Cₗ


### Example 3 — Orbital Mechanics

Problem:

A satellite orbits Earth at altitude 500 km.

Earth radius = 6371 km  
Gravitational constant μ = 3.986 × 10¹⁴  

Find orbital velocity.

Formula:

v = √(μ / r)
