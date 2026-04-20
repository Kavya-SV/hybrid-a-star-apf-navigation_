# Hybrid A*-APF Navigation Framework for Indoor Robot Motion

This repository contains the implementation of a hybrid path planning framework that combines **A\*** search and **Artificial Potential Fields (APF)** for real-time indoor robot navigation.

The project focuses on generating **curvature-continuous, smooth, and collision-free trajectories** while overcoming limitations such as local minima and zigzag motion.

---

## Repository Structure

- `notebooks/` – Simulation and algorithm implementation  
- `dataset/` – Path plots and trajectory examples
- `requirements.text/` - required things 

---

## Algorithms Used

- A* Search Algorithm (global path planning)  
- Artificial Potential Field (local obstacle avoidance)  
- Hybrid A*-APF Integration Strategy  
- Path Smoothing & Anti-Zigzag Optimization  

---

## Features

- Real-time indoor navigation capability  
- Curvature-continuous trajectory generation  
- Reduced oscillations using anti-zigzag smoothing  
- Effective obstacle avoidance using APF forces  
- Improved path stability compared to standalone A* or APF  

---

## Methodology

The framework integrates global and local planning techniques:

- **A\*** computes the optimal shortest path from source to destination  
- **APF** refines the path using attractive and repulsive forces  

### Hybrid Mechanism Ensures

- Smooth transitions  
- Avoidance of local minima issues  
- Continuous and stable robot motion  

### Additional Enhancements

- Trajectory smoothing for curvature continuity  
- Reduction of abrupt directional changes  
- Stability optimization for real-time execution  

---

## Results

The hybrid approach demonstrates:

- Smoother trajectories compared to standalone A*  
- Reduced zigzag motion and oscillations  
- Improved obstacle avoidance performance  
- Enhanced real-time navigation capability in indoor environments  

---

## Reproducibility

All simulations were implemented in **Python**.

### To reproduce results:

1. Install dependencies  
2. Run the main simulation script or notebooks  
3. Visualize generated paths and trajectory outputs  

---

## Visualizations

- Path comparison between A*, APF, and Hybrid model  
- Trajectory smoothness analysis  
- Obstacle avoidance demonstrations  

These visualizations highlight the improved performance and stability of the hybrid navigation framework.
