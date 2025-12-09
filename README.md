Variational Quantum Eigensolver (VQE) for Molecular Ground State Energy

This project implements a Variational Quantum Eigensolver (VQE) using Cirq and OpenFermion to compute the ground state energy of molecules.
It also compares the VQE results with Full Configuration Interaction (FCI) values for validation.

🧪 Project Overview: 
The Variational Quantum Eigensolver (VQE) is a hybrid quantum-classical algorithm used to approximate the ground state energy of quantum systems such as molecules.
In this project:
1. You input the number of molecules and atoms.
2. The system computes bond distances and checks which distance gives the minimum ground state energy.
3. Uses OpenFermion to generate Hamiltonians.
4. Uses Cirq to build parameterized quantum circuits.
5. Compares VQE energy vs FCI energy and plots energy curves to visualize convergence.

✨ Features

🔹 Compute molecular Hamiltonians using OpenFermion

🔹 Build parameterized VQE ansatz circuits with Cirq

🔹 Optimize circuit parameters using classical optimizers

🔹 Plot Energy vs Iterations

🔹 Plot FCI vs VQE Energy curves

🔹 Identify optimal bond lengths

🔹 Simple and modular code (easy to extend)

🧰 Tech Stack
Component	Technology
Quantum Simulation	Cirq
Quantum Chemistry	OpenFermion
Optimizers	SciPy
Plots	Matplotlib
Programming Language	Python

🚀 How to Run
1. Install Dependencies
pip install cirq openfermion scipy matplotlib numpy
2. Run the Program
If using Python file:
      python main.py
If using Jupyter notebook:
      jupyter notebook
3. Enter Your Molecule Data
Example:
Number of atoms: 2
Atom 1: H (0,0,-0.37)Å
Atom 2: H (0,0,0.37)Å


📉 Outputs
1. Computes the ground state energy of the molecule using VQE.
2. Generates the exact FCI energy for comparison.
3. Produces a VQE convergence graph.
4. Plots a FCI vs VQE energy curve across different bond distances.
5. Detailed circuit diagram 
