# Hovercraft Trajectory Optimization with Velocity Matching

## Overview
This project models and optimizes the trajectories of two hovercrafts — Alice and Bob — to achieve a rendezvous with matched velocities. Using **Julia** and the `Ipopt` nonlinear optimization library, the program minimizes total energy consumption while satisfying motion dynamics and velocity constraints.

## Objective
- Model hovercraft motion over time with position, velocity, and thrust inputs.
- Minimize the total energy required for both vehicles.
- Achieve a smooth rendezvous point with velocity matching.

## Methods
- **Programming Language:** Julia  
- **Libraries Used:** JuMP, Ipopt, LinearAlgebra, Plots  
- **Optimization Type:** Nonlinear programming  
- **Visualization:** 2D trajectory plotting with final velocities  

## Key Results
- Rendezvous Point: (0.15, 0.167) miles  
- Final Velocity: 55.93 mph  
- Alice's Energy: 112.993  
- Bob's Energy: 112.993  

## Visualization
The hovercraft trajectories are visualized below:

![Hovercraft Trajectories](results_plot.png)

## Learnings
Through this project, I gained experience in:
- Defining optimization problems with dynamic constraints
- Applying control theory concepts using Julia
- Visualizing simulation results for interpretability

## Author
**Ingrid Buiceag-Arama**  
_Data Science & Consumer Behavior Graduate | Interested in data modeling, analytics, and UX-focused data visualization_
