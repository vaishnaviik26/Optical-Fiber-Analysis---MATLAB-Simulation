# Optical-Fiber-Analysis - MATLAB-Simulation

This project simulates basic optical fiber communication using MATLAB. It covers core aspects such as:

- Bit generation
- NRZ signal transmission
- Attenuation (loss)
- Dispersion (pulse broadening)
- Noise (channel distortion)
- Bit Error Rate (BER) calculation

## Topics Covered

### 1. Optical Fiber Communication
- A method of transmitting information as pulses of light through glass/plastic fibers.
### 2. NRZ (Non-Return-to-Zero) Encoding
- A line coding format where:
  - Bit '1' = High signal
  - Bit '0' = Low signal
- Maintains constant voltage for the entire bit duration.
### 3. Attenuation
- Reduction in signal power as it travels through fiber.
### 4. Dispersion
- Broadening of the pulse over time, leading to inter-symbol interference.
- In this simulation, dispersion is modeled by convolution (smoothing/blurring filter).
### 5. Noise
- Random variations (usually modeled as Gaussian noise) that distort the signal.
- Simulated using `randn()` in MATLAB.
### 6. Bit Error Rate (BER)
- Measures the accuracy of transmission.

# **Output**

Blue Line → Transmitted NRZ signal

Orange Line → Received signal after attenuation, dispersion, and noise

BER (Bit Error Rate) → Printed as output

# **Author**

Vaishnavi Kamat

B.E. Electronics & Telecommunication Engineering

PVG COET Pune

