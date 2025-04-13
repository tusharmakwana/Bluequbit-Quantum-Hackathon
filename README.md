# Bluequbit-Quantum-Hackathon
Welcome to the BlueQubit Quantum Hackathon! Use your quantum computing skills to crack our peak circuits and earn points along the way. The challenge is ongoing, and the difficulty of the circuits will increase as you progress. The aim is to find the peak bitstring that has the maximum amplitude, standing out from the rest of the exponentially small amplitudes!

Challenge Details
Time Left: 13:55:40 (and counting...)
How to Participate
Download the QASM files for each problem. The circuits will progressively increase in difficulty.
Find the peak bitstring: This is the bitstring with the maximum amplitude, which stands out the most from the exponentially small amplitudes.
Submit your answer: Use the Submission tab to submit the peak bitstring. Both the peak bitstring and its reverse will be accepted as correct, so you don’t need to worry about bit ordering.
Use the provided script to load the .qasm2 files into Qiskit.
Sample Script to Load QASM Files in Qiskit
from qiskit import QuantumCircuit

# Load the circuit from a QASM file
qc = QuantumCircuit.from_qasm_file('P1.qasm')
Problems
Problem 1: Little Peak 🌱 Points: 10 Take your first quantum leap with this elegantly simple 4-qubit circuit. Download the QASM file: P1_little_peak.qasm

Problem 2: Swift Rise 🌊 Points: 20 Accelerate your journey with this electrifying 28-qubit circuit. Download the QASM file: P2_swift_rise.qasm

Problem 3: Sharp Peak 🏜 Points: 50 Conquer the frontier with this razor-sharp 44-qubit circuit, meticulously crafted to slice through classical barriers and redefine the quantum landscape. Download the QASM file: P3_sharp_peak.qasm

Problem 4: Golden Mountain ⛰️ Points: 100 Ascend to dazzling heights with this majestic 48-qubit circuit, where every connection gleams like a golden pathway to quantum brilliance. Download the QASM file: P4_golden_mountain.qasm

Problem 5: Granite Summit 🗻 Points: 200 Carve your legacy on this steadfast 44-qubit circuit, as enduring as granite itself, inviting you to seize the summit of quantum ingenuity. Download the QASM file: P5_granite_summit.qasm

Problem 6: Titan Pinnacle 🌋 Points: 290 Unleash a torrent of quantum power with this monumental 62-qubit circuit—a volcanic marvel that erupts with the explosive brilliance of technological innovation. Download the QASM file: P6_titan_pinnacle.qasm
