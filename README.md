# Quantum Circuit Translator for QOSF Mentorship Program Task 3

This is a quantum circuit compiler and optimizer which converts any given Cirq circuit made up of the basic gates: I, S, H, X, Y, Z, RX, RY, RZ, CNOT, CZ into a combination of our fundamental gates: RX, RZ, and CZ. It also optimizes to reduce the overhead generated after compilation, for example: `--RX(pi/2)-RX(pi/2)--` will be converted to `--RX(pi)--`.

Required libraries:
* Cirq, installation instructions can be found [here](https://cirq.readthedocs.io/en/stable/install.html).

This program was created as a result of completing a task for Quantum Open Source Foundation's Mentorship Program. Link to that can be found [here](https://qosf.org/qc_mentorship/).

Refer `task_3.html` for description and implementation of the program or `task_3.ipynb` Jupyter Notebook for an interactive session.
