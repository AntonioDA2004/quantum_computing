# Quantum Circuits: Bell State & 5-Qubit Quantum Fourier Transform (QFT)

This repository contains example quantum circuits implemented using Qiskit:
- A 2-qubit circuit that creates a Bell state (maximally entangled pair).
- A 5-qubit circuit demonstrating the Quantum Fourier Transform (QFT).

---

## Bell State Quantum Circuit

This simple circuit generates a Bell state, a fundamental entangled state in quantum computing.

### Description

- Applies a Hadamard gate to qubit 0 to create superposition.
- Applies a CNOT gate with qubit 0 as control and qubit 1 as target to entangle the two qubits.

The resulting state is a maximally entangled Bell state, useful for quantum algorithms and communication protocols.

---

## 5-Qubit Quantum Fourier Transform (QFT) Circuit

This example shows the QFT, which transforms quantum states into their frequency domain representation.

### Description

- Prepares 5 qubits in states encoding different frequencies.
- Applies the QFT to convert wave-like amplitude patterns into sharp spikes that indicate frequency.
- Demonstrates how the QFT functions as an efficient frequency detector, crucial for algorithms like Shor’s algorithm and phase estimation.

---

## Usage

Run the respective circuit codes in Qiskit to build, simulate, and visualize the circuits. Use Qiskit’s built-in drawing and simulation tools to explore the behavior and outcomes of the quantum transformations.

---

Feel free to extend and experiment with these circuits for deeper quantum computing learning and applications.
