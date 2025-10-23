Comparative Study of Quantum Teleportation and Superdense Coding Protocols:

This project presents a comparative study of two fundamental quantum communication protocols — Quantum Teleportation and Superdense Coding — implemented using Qiskit.
Both protocols demonstrate the power of quantum entanglement in transmitting information more efficiently than classical methods.

Overview:

1. Superdense Coding

Superdense Coding allows 2 classical bits to be transmitted using 1 qubit by leveraging a shared entangled pair between Alice and Bob.
Steps involved:

Entanglement Creation: Alice and Bob share an entangled Bell pair.

Message Encoding: Alice applies X/Z gates based on her 2-bit message.

Transmission: Alice sends her qubit to Bob.

Decoding: Bob performs operations to retrieve the original 2-bit message.

Visualization includes:

Quantum circuit diagram

Measurement results histogram

2. Quantum Teleportation

Quantum Teleportation allows an arbitrary quantum state (|0⟩, |1⟩, |+⟩, |−⟩) to be transferred from Alice to Bob without physically sending the qubit.
Steps involved:

Entanglement Creation: Bob and Alice share an entangled pair.

Bell Measurement: Alice performs a joint measurement on her qubits.

Classical Communication: Alice sends 2 classical bits to Bob.

State Reconstruction: Bob applies corrective gates (X, Z) to obtain the original state.

Visualization includes:

Quantum circuit diagram

Measurement histogram

Bloch sphere showing Bob’s qubit state before measurement

Tech Stack

Language: Python

Quantum SDK: Qiskit

Visualization: Matplotlib, Qiskit Visualization Tools

Simulator: AerSimulator

Outputs

Quantum circuit plots for each protocol

Measurement histograms showing final states

Bloch sphere for visualizing quantum state orientation
