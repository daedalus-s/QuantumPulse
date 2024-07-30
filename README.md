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
 - 
## Key Features
 - Standard Bell Pair Circuit
 - Implementation using Hadamard and CNOT gates
 - Pulse-based Implementation
 - Custom Hadamard gate decomposition
 - CZ gate using arbitrary waveforms
 - Phase correction for qubit frames
 - 
## Visualizations
 - CZ gate waveform
 - Complete pulse sequence

## Execution and Analysis
Running circuits on Rigetti's Aspen M-3
Comparison of measurement results

## Usage
 - Open the Jupyter notebook Bell_Pair_Pulse.ipynb
 - Follow the cells sequentially to understand the implementation and see results
 - Modify parameters or pulse shapes to experiment with different configurations

## Results
 - The notebook demonstrates successful creation of Bell states using both methods, with visualizations and analysis of the results.
 - 
### Cost Considerations
 - The notebook includes an estimation of costs for running quantum tasks. Be aware of potential charges when using the Rigetti quantum device through Amazon Braket.
