# F-16 Dynamic Modeling and Simulation (0–0.6 Mach)

This project focuses on the **dynamic modeling and basic pitch/roll/yaw control of the F-16 fighter aircraft** in the subsonic flight regime (Mach 0–0.6), based on the NASA technical report:

> **Nguyen, L. T., Ogburn, M. E., Gilbert, W. P., Kibler, K. S., Brown, P. W., & Deal, P. L. (1979).**  
> *Simulator Study of Stall/Post-Stall Characteristics of a Fighter Airplane With Relaxed Longitudinal Static Stability*. NASA TP-1538.

## 🔧 Project Description

The simulation aims to capture the 6 degree of freedom dynamics of the F-16 using realistic aerodynamic and propulsion data derived from the NASA report. The data is provided in `.mat` files, which must be loaded before running the model.

> ⚠️ **Note:** Pitch control need an update.

## 📦 Requirements

To run the simulation environment, ensure the following software and hardware are available:

- **MATLAB** with:
  - Aerospace Blockset
  - Aerosim Blockset   
  - Simulink 3D Animation (for FlightGear integration)
- **FlightGear** (open-source flight simulator)
- **Joystick** (for manual flight control input)

## 🚀 How to Run

1. Clone or download the repository.
2. Open MATLAB and run the script to load engine and aerodynamic data (`.mat` files).
3. Connect your joystick and ensure it is configured correctly in MATLAB.
4. Launch **FlightGear**, verify it is listening for external Simulink input.
5. Open the Simulink model and start the simulation.

## 📚 Reference

NASA Technical Report TP-1538 (1979)
