# Analog Function Generator

This repository contains the project details for the **Analog Function Generator**, completed as part of the Semester 3 EN2091 - Laboratory Practice and Projects module. The project involved designing and implementing a fully functional analog function generator capable of producing various waveforms with adjustable parameters.

## Project Overview

The analog function generator includes the following functionalities:
- Generation of sine, square, triangular, sawtooth, and PWM waveforms.
- Adjustable frequency range: 20 Hz to 20 kHz.
- Adjustable amplitude: 0 V to 20 V peak-to-peak.
- Pulse Width Modulation (PWM) with duty cycle variation from 1% to 99%.
- DC offset adjustment.
- Capability to drive a 50 Ω load.

## Key Features
1. **Waveform Generation**:
   - Square and PWM waveforms using a Schmitt trigger circuit.
   - Triangular and sawtooth waveforms using capacitor charging/discharging circuits.
   - Sine wave using a Wien bridge oscillator.

2. **Output Circuitry**:
   - Amplitude control via an inverting amplifier.
   - Class-AB push-pull amplifier for driving loads without distortion.
   - Waveform and probe selection switches.

3. **Design Specifications**:
   - Designed using op-amps, resistors, capacitors, transistors, and potentiometers.
   - Components selected based on precise calculations and simulations.

## Development Stages
1. **Electronic Design**: Circuits were designed to meet the required specifications.
2. **Simulations**: Circuit behavior was verified using NI Multisim.
3. **Testing**: Breadboard implementation revealed minor issues, which were resolved with decoupling capacitors and stable connections.
4. **PCB Design and Fabrication**:
   - Two-layer PCB designed in Altium Designer.
   - Soldering and testing were performed to ensure proper functionality.
5. **Enclosure Design**: Enclosure modeled using SolidWorks for housing the circuit securely.

## Results
- Successfully generated sine, square, triangular, sawtooth, and PWM waveforms within the specified frequency and amplitude ranges.
- Minor waveform distortions observed at high frequencies, which can be improved with higher-quality components.

## Acknowledgments
We express our gratitude to our project mentors for their guidance and support throughout the development process.

---

### Directory Structure
- **/Reports**: Project documentation and detailed reports.
- **/Altium Files**: Schematics and PCB Files.
- **/SolidWorks Designs**: Enclosure design files.
- **/Simulations**: Simulation files and results.

### How to Use
1. Review the design files and schematics to understand the circuit.
2. Use the PCB design files for fabrication.
3. Refer to the project documentation for detailed instructions and analysis.

---

This project showcases the application of analog design concepts in creating a practical and reliable function generator.
