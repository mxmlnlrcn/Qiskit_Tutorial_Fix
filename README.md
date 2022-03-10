# Qiskit_Tutorial_Fix
Learning about quantum circuits I found an issue in the Qiskit's tutorial described below, so I implement the circuit on my own and I uploded it here

```python
# Textbook: Learn Quantum Computation using Qiskit
# Title: Grover's Algorithm
# link: https://qiskit.org/textbook/ch-algorithms/grover.html#2.-Example:-2-Qubits-
# Section: "3.1 Qiskit Implementation"
# Capture: https://drive.google.com/file/d/13Di3TQ9PH_kta-Q4p6Vi8bdoXgIlNAMO/view?usp=sharing
# Date: 13Th September 2022

# Issue: When I try to implement the circuit I run into the next problem

# ---------------------------------------------------------------------------
# NameError                                 Traceback (most recent call last)
# <ipython-input-30-e3ba7032658b> in <module>
#      30 n = 3
#      31 grover_circuit = QuantumCircuit(n)
# ---> 32 grover_circuit = initialize_s(grover_circuit, [0,1,2])
#      33 grover_circuit.append(oracle_ex3, [0,1,2])
#      34 grover_circuit.append(diffuser(n), [0,1,2])

# NameError: name 'initialize_s' is not defined
```
