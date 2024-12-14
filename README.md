## ECE 4869 - Power Electronics
Elizabeth Woo - August 11th, 2024

## Final Project: Power Electronics Design - 11.1V to 5V Buck Converter 
![image](https://github.com/user-attachments/assets/cf184f6d-2a3a-4d0e-b49e-7d1021d31566)


## Objective 
To apply the course theory to design, implement and analyze a relevant device or a system

## Project Requirements 
The project must be completed using MATLAB/Simulink/Simscape Power Systems. Analytical hand
calculation may be used for analyses and for presenting the results in the project report.

<ins>1. Design of a device or a system</ins>
- Design a device or a system that is based on one of the device/systems covered in the course. They include
DC-DC converters, DC power supplies, rectifier, inverter, and HVDC transmission system. The main
requirements are as follows:
  - Parameters: The device/system must be appropriate/realistic where all pertinent parameters
must be specified. It is preferable that parameters of a real-world device/system are used.
References (e.g. publications, online sources, manufacturer data etc.) must be provided if you
use data from the sources. The device/system pertinent parameters shall be provided in a table
similar to the Table 1 below.
  - A circuit diagram for the designed device/system must be drawn and included in the report. 
  - Rationale must be provided to justify the design (e.g. the need for the device/system, its benefit,
its applications, reason/rule of thumb for parameter selection etc.)
  - Output calculation: Using the system design parameters, calculate its pertinent outputs to
confirm that desired outputs are obtained. Include all the calculations and results in the report.

<ins>2. Simulation and analysis of designed device/system</ins>
- Perform the following tasks:
  -1. Build your designed device/system using MATLAB Simulink Simscape. Simulate the device/system
and record the system outputs.
  -2. Compare the simulated outputs with the calculated outputs in Part 1. Provide your observation and
analysis (e.g. whether your Simulink-based system performs as expected, any limitation or necessary
improvement etc.)
  -3. Include all outcomes from Step 1 and Step 2 in the report.
  -4. Save and submit the project Simulink file.
- Analysis and reduction of harmonics:
  - A power electronic system typically requires filter(s) to reduce harmonics. In case a filter is designed, the
following requirements apply:
  - 1) Analysis of harmonics: Use “FFT analysis” in “Powergui/Tools” to measure THD and harmonic
spectrum.
  - 2) Reduction of harmonics: Based on the FFT analysis report, design a filter to reduce the unwanted
harmonics. The filter design must include its circuit diagram, transfer function, calculation and
obtained parameters (e.g. capacitor and inductor values if using an LC-filter). No ready-made filter
by Simulink is accepted
