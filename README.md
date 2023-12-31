# BB84 Implementation

This is an implementation of the BB84 quantum-key distribution protocol in Python using IBM’s Qiskit SDK.
Took help from the qiskit textbook: https://github.com/Qiskit/textbook/blob/main/notebooks/ch-algorithms/quantum-key-distribution.ipynb

Run the file, and it will perform the protocol and gives out-put of:

- time taken to execute the protocol
- a boolean indicating whether the protocol worked successfully
- the keys that Alice and Bob have

The protocol evaluates the quantum circuit using a simulator.
