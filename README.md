# Project-C-Star-Data-Acquisition-Unit
This repository contains the raw code used to collect data from two platform load cells to measure the mass flowrate of two liquid propellants for a 1.5 kN bipropellant liquid rocket engine.

[1] Load Cell Calibration Code [Arduino IDE]
Use this to calibrate any load cell (with an excitation voltage of no greater than 5 VDC) connected to an arduin/elegoo with a HX711 amplification module.

[2] Load Cell Main Arduino Script [Arduino IDE]
Use this to upload a script with the specific load cell calibration constants from [1] to the arduino/elegoo alongside a microSD card reading. It will print a new dataset each time the power is removed and returned.

[3] Load Cell Data Analysis Code [MATLAB]
This code simply taked the raw oxidiser and fuel load cell data from each load cell, and plots the mass and mass-flowrate over time, smoothing the data as necessary.
