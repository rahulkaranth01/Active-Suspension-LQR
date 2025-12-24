# Active-Suspension-LQR
Active Suspension Control System design using LQR and Kalman Filtering in MATLAB/Simulink. Optimized for a C-Segment vehicle, achieving faster settling time with high energy efficiency.

Project Overview
This repository contains the design and simulation of an Active Suspension Control System applied to a 2-DOF Quarter-Car Model. The project investigates the application of Modern Control Theory (Linear Quadratic Regulator) to optimize the trade-off between passenger comfort and vehicle handling for a standard C-Segment passenger car.

Key Features:

Optimal Control: Implementation of LQR to minimize vertical chassis acceleration.

State Estimation: Integration of a Kalman Filter to handle noisy sensor data.

High Efficiency: Achieved critical damping with a peak control effort of only 300 N (approx. 10% of actuator capacity).

Performance: Reduced oscillation settling time by 40% compared to the passive baseline.
