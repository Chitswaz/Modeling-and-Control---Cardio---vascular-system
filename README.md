# Windkessel Model for Cardiovascular System and Control of Hypertension in MATLAB

## Introduction
This repository contains MATLAB code for modeling the cardiovascular system using the Windkessel model and investigating the effects of parameter changes and controller design on blood pressure. The model simulates the dynamics of blood flow and pressure in the cardiovascular system, including the effects of resistance, compliance, and heart rate. The code also explores the impact of hypertension (increased blood pressure) and demonstrates how a PID controller can be used to regulate blood pressure.

## Files Included
- `windkessel_model.m`: Main MATLAB script that implements the Windkessel model and performs simulations.
- `impulse_response.m`: Function to compute and plot the impulse response of the Windkessel model.
- `half_rectified_wave.m`: Function to generate and plot a half-rectified sine wave representing cardiac output.
- `hypertension.m`: Function to simulate and plot the effects of increased resistance (R) and decreased compliance (C) on blood pressure.
- `controller_design.m`: Function to design and evaluate a PID controller for regulating blood pressure.

## Instructions
To run the simulations and generate the plots, follow these steps:

1. Clone or download the repository to your local machine.
2. Open MATLAB and navigate to the directory where the files are saved.
3. Run the main script `windkessel_model.m` by typing its name in the MATLAB command window.
4. Follow the prompts and instructions in the script to specify parameters and simulation options.
5. The script will generate and display various plots illustrating the system's behavior under different conditions.

## Results
The code produces several plots that demonstrate the following:

- Impulse response of the Windkessel model
- System response to a half-rectified sine wave input representing cardiac output
- Effects of increased resistance (R) and decreased compliance (C) on blood pressure, simulating hypertension
- Step response of the closed-loop system with a PID controller for blood pressure regulation

## Conclusion
This MATLAB code provides a comprehensive exploration of the Windkessel model for the cardiovascular system and its response to various parameter changes and controller interventions. It serves as a valuable resource for understanding the dynamics of blood flow and pressure, as well as the potential for using control techniques to manage hypertension.
