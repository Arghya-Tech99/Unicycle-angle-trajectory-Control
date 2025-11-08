# Trajectory Tracking and Stabilization of a Non-Holonomic Unicycle Robot

The unicycle control problem is a benchmark challenge in control systems due to its inherent nonholonomic and unstable nature, requiring the simultaneous execution of dynamic stabilization (balancing) and complex trajectory tracking. This project presents a comprehensive study on the stabilization and trajectory control of a challenging non-holonomic system: the self-balancing unicycle. 

This work focuses on the design and implementation of a robust control architecture capable of simultaneously managing the system's inherent instability—by regulating the critical balance angles (pitch and roll)—and ensuring highly accurate tracking of a predefined reference trajectory. The resulting control strategy precisely dictates the unicycle's velocity and steering inputs, achieving dynamic equilibrium while maintaining fidelity to the desired path.

## Diagrams

## Results and Files

Project files, including the main MATLAB scripts, Simulink model, and PSO tuning function for the PID controller, are listed here.

- MATLAB files for tuning the PID controller using PSO.
- MATLAB file for cost function calculation during the tuning of the controller.
- Simulink models and cache files for Roll angle control and Pitch angle control for the unicycle (Non-linearized and Feedback linearized models).
- Simulink model and cache files uploaded for the velocity control of the unicycle.
- MATLAB file for implementation of the optimal LQC (Linear Quadratic Control) algorithm.
- Response curves of all the systems.

## Acknowledgements and References

 - [Control Tutorials for MATLAB](https://ctms.engin.umich.edu/CTMS/index.php?example=InvertedPendulum&section=SystemModeling)
 - [M. A. Basal and M. F. Ahmed, "Mathematical Modeling of a Unicycle Robot and Use of Advanced Control Methodologies for Multi-Paths Tracking Taking into Account Surface Friction Factors," J. Robotics Control (JRC), vol. 6, no. 1, pp. 142-154, 2025.](https://www.researchgate.net/publication/391699621_Mathematical_Modeling_of_a_Unicycle_Robot_and_Use_of_Advanced_Control_Methodologies_for_Multi-Paths_Tracking_Taking_into_Account_Surface_Friction_Factors)
 - [N. A. Majid, Z. Mohamed, and M. A. M. Basri, "Velocity control of a unicycle type of mobile robot using optimal PID controller," Jurnal Teknologi, vol. 78, no. 7-8, pp. 119-124, Jul. 2016.](https://www.researchgate.net/publication/305698356_Velocity_control_of_a_unicycle_type_of_mobile_robot_using_optimal_pid_controller)

## Authors

- [@Arghya-Tech99](https://github.com/Arghya-Tech99)


