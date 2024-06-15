# Independent-Joint-Control-of-Last-Joint-of-SCORA-Robot-
 Controlled SCORA robot's last joint using Arduino Uno, MATLAB Simulink with PI controller, achieving precise position and velocity control, with graphical analysis and future improvement insights.
 # Independent Joint Control of Last Joint of SCORA Robot

This repository contains the project files for controlling the last joint of a SCORA robot using Arduino Uno and MATLAB Simulink. 

## Abstract

This project focuses on implementing position and velocity control of the SCORA robot's last joint using a PI controller. MATLAB Simulink is utilized for real-time parameter tuning and performance analysis through graphs.

## Introduction

The project aims to control the industrial SCORA robot's final joint for precise movements in manufacturing and automation tasks. Utilizing an Arduino Uno and L298N motor driver, along with an encoder, the system achieves controlled linear motion.

## Methods

### Components Used:
- Arduino Uno
- L298N Motor Driver
- HEDS-5550-I#14 Encoder
- DC Motor for Linear Axis Movement
- Jumper Wires

### Procedure:
1. Study robot dynamics and component documentation.
2. Test motor and encoder functionality using MATLAB IDE and Simulink.
3. Implement closed-loop control using PI controller in Simulink.
4. Tune controller parameters (Kp, Ki) for optimal performance.
5. Analyze results through graphs for position and velocity modes.

## Results

### Position Mode:
- Achieved minimal error with no overshoot.
- Graphical representation shows precise motor displacement.

### Velocity Mode:
- Adjusted PWM signals for varied motor speeds.
- Graphical analysis depicts speed change dynamics.

## Conclusion

The project successfully demonstrates precise joint control using MATLAB Simulink and Arduino Uno. Future improvements include scalability with NI-DAQ cards and implementing trajectory-based motion.

## Limitations and Improvements

### Limitations:
- Insufficient documentation on robot specifics.
- Connectivity issues with scalable controllers.

### Improvements:
- Incorporate NI-DAQ cards for enhanced control.
- Implement trajectory planning for multi-point motion.

For detailed documentation, refer to the project report and MATLAB scripts.


