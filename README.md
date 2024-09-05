# Mechanical Systems Analysis Projects

This repository contains a collection of my personal projects for mechanical systems analysis, aligned with the coursework I am completing. The projects cover a variety of topics from kinematics to dynamics, focusing on the application of theoretical principles to practical problems.

## Projects Contents Overview

### 1. Project 1 - Parallel Manipulator Kinematic Analysis
- **Project File:** `jacopo.dallafior.218931.homework1.nb`
- **Description:** This project focuses on the kinematic analysis of a parallel manipulator. The project covers both forward and inverse kinematics, where the position and orientation of the end-effector are determined and analyzed based on the known or desired actuator displacements. It also includes visualization of the manipulator’s movements.
- **Key Concepts:**
  - **Forward Kinematics:** The project implements a procedure to determine the position and orientation (x, y, and θ) of the end-effector (point E) given the known values of the actuator positions \( s_1, s_2, s_3 \). The methodology is based on adaptations of quadrilateral and pentagonal linkage studies.
  - **Velocity and Angular Velocity:** The velocity of point E and the angular velocity of the gripper are calculated using methods covered in class. The analysis is essential for understanding how fast the end-effector can move within a given workspace.
  - **Acceleration and Singularities:** The accelerations of point E are derived, and the system’s singular configurations are identified. Singular configurations are crucial because they represent points where the manipulator loses certain degrees of control.
  - **Inverse Kinematics:** A procedure is developed to solve the inverse kinematics problem, determining the required actuator displacements \( s_1, s_2, s_3 \) for a given desired position (x, y, θ) of the end-effector. This part of the analysis is vital for control and manipulation tasks in robotic systems.
  - **Interactive Visualizations:** Animations are created to visualize the forward and inverse kinematic solutions, allowing an interactive exploration of how the manipulator moves and reaches different configurations based on the input parameters.


### 2. Project 2 - Dynamic Analysis of a Two-Phase System
- **Project File:** `project2.nb`
- **Description:** This project examines the dynamic behavior of a mechanical system in two different phases. It includes the derivation and solution of the equations of motion, with an emphasis on reaction     forces and the optimization of system parameters. The project also focuses on simulating and visualizing system behavior.
- **Key Concepts:**
  - **Equations of Motion:** The project starts by deriving the equations of motion for a mechanical system in two distinct phases, analyzing the system’s degrees of freedom.
  - **Reaction Forces:** The calculation of reaction forces, including the ground's normal force on one of the masses, is essential to understanding the system’s behavior under different conditions.
  - **Initial Conditions:** Identifying the initial conditions for the system before solving the equations of motion, ensuring correct simulation from the start.
  - **Numerical Integration:** The integration of the motion equations is performed, with special attention to detecting critical points (such as when a mass detaches from the ground). The integration is halted        at these points using appropriate mathematical conditions.
  - **Second Phase Dynamics:** For the second phase of the system's motion, the project explores the system's dynamics after detachment, analyzing reaction forces and solving for three degrees of freedom.
  - **Optimization and Graphical Representation:** The project includes an analysis of system behavior at the moment of detachment, including tension in a connecting rope and optimization of parameters (e.g.,          mass) to maximize the range of the system.
  - **Simulation and Visualization:** Finally, animations and visualizations are generated to illustrate the system’s motion during both phases, with a particular focus on optimizing the system for maximum range.


### 3.3. Project 3 - Mechanism Simulation and Optimization
- **Project File:** project3.nb`
- **Description:** This project involves simulating a trebuchet, calculating the range, and optimizing the configuration for maximum range. It includes numerical integration to simulate the two phases of trebuchet motion and takes into account failures due to parameter combinations. The project also explores optimizing the range using different techniques and adjusting search intervals to achieve a solution with a range greater than 800 meters.
- **Tasks Performed:**
  - Implement a function to simulate the trebuchet's range based on parameter configurations, considering constraints that may result in zero-range solutions.
  - Optimize the trebuchet's range by varying parameters like \( h, L, L1, L2, m2, L3 \), ensuring that the initial configuration is feasible.
  - Fine-tune the optimization process by starting with small intervals around the initial homework configuration and iterating to find the optimal solution.
  - Create an animation showing the configuration with the maximum range during the optimization process.
  - Adjust search intervals multiple times to find a solution with a range greater than 800 meters.


## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jacopodallafior/mechanical-systems-projects.git
