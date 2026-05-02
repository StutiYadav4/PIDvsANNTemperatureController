# 🤖 ANN vs PID Controller for Temperature Control

## Overview
This project compares a traditional PID controller with an Artificial Neural Network (ANN) controller for temperature control in an industrial process system.

## What I Did
- Implemented a PID controller and tuned it using the Ziegler–Nichols method  
- Built a feedforward ANN trained on PID-generated data  
- Simulated a temperature control system with dead time  
- Compared controller performance under different conditions  
- Tested robustness using variable dead time scenarios  
- Explored advanced models: Residual ANN and LSTM-based controller  

## System Description
- Closed-loop temperature control system  
- Error-based control using feedback  
- Controller output converted to PWM signal for heater control  
- Continuous monitoring and adjustment of system response 

## Tools & Technologies
- Python (simulation & modeling)  
- Neural Networks (ANN, Residual ANN, LSTM)  
- Control Systems (PID, Ziegler–Nichols tuning)  
- MATLAB concepts / control theory fundamentals  

## Objective
To analyze and compare classical and data-driven control approaches for handling nonlinear and time-varying systems.
