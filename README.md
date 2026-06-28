# Quantum Fourier Transform Demo
A step‑by‑step walkthrough of the Quantum Fourier Transform (QFT) using Qiskit and Dirac‑notation derivations.  
This repository contains a Jupyter notebook that reconstructs the QFT for the example input ∣7⟩ on 3 qubits in three parallel ways:

- using Qiskit’s built‑in synth_qft_full implementation
- building the QFT circuit gate‑by‑gate manually
- deriving the wavefunction evolution analytically in Dirac notation, gate by gate

The notebook demonstrates how all three approaches lead to the same final state (up to global phase).

The goal is to provide a clear, educational reference for learners who want to understand how QFT works internally rather than treating it as a black box.

A follow‑up notebook will extend this foundation toward the modular QFT adder, showing how QFT enables modular arithmetic in quantum algorithms such as Shor’s algorithm.
