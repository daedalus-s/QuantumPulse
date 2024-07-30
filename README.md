# QuantumPulse

## Bell Pair Creation with Pulses on Rigetti's Aspen M-3
- This repository contains a Jupyter notebook demonstrating the creation of Bell states using both standard gate-based methods and low-level pulse sequences on Rigetti's Aspen M-3 quantum device via Amazon Braket.

## Overview
The notebook explores:
- Implementation of a Bell pair circuit using standard quantum gates
- Creation of the same Bell state using pulse-level control
- Comparison of results between gate-based and pulse-based approaches
## Requirements
Python 3.x
Amazon Braket SDK
Numpy
Matplotlib

## Installation
 - Clone this repository:
 - git clone https://github.com/yourusername/bell-pair-pulses-rigetti.git

 - Install required packages:
 - pip install amazon-braket-sdk numpy matplotlib
## Key Features
 - Standard Bell Pair Circuit
 - Implementation using Hadamard and CNOT gates
 - Pulse-based Implementation
 - Custom Hadamard gate decomposition
 - CZ gate using arbitrary waveforms
 - Phase correction for qubit frames
 - Analyze the impact of noise by introducing a depolarizing channel
 - Implement error mitigation using stabilizer averages
 - Optimize pulse parameters to maximize fidelity
## Visualizations
 - CZ gate waveform
 - Complete pulse sequence

## Execution and Analysis
 - Running circuits on Rigetti's Aspen M-3
 - Comparison of measurement results

## Usage
 - Open the Jupyter notebook Bell_Pair_Pulse.ipynb
 - Follow the cells sequentially to understand the implementation and see results
 - Modify parameters or pulse shapes to experiment with different configurations

## Results
 - The notebook demonstrates successful creation of Bell states using both methods, with visualizations and analysis of the results.
 - Pulse-based Bell state preparation achieved 88.4% fidelity (500 shots)
 - Gate-based implementation achieved 84% fidelity
 - Depolarizing noise (p=0.1) degraded fidelity to 72.2%
 - Error correction with stabilizer encoding improved noisy fidelity to 74%
 - Optimized CZ pulse parameters further improved noiseless fidelity to 88%
## Analysis
 - Pulse-level control allows for high-fidelity Bell state preparation with modestly better performance than gate-based approaches. However, sensitivity to noise and decoherence remains a significant challenge. Stabilizer error correction and pulse optimization provide some improvements, but further work is needed to dramatically enhance robustness to errors.
### Cost Considerations
 - The notebook includes an estimation of costs for running quantum tasks. Be aware of potential charges when using the Rigetti quantum device through Amazon Braket.
## Future Directions
 - Apply more sophisticated pulse optimization techniques (e.g., GRAPE)
 - Explore dynamical error suppression techniques
 - Integrate pulse-level control with noise-robust circuit compilation
 - Investigate scalable entanglement generation for quantum networking
