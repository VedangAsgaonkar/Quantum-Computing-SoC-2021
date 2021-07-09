# Quantum-Computing-SoC-2021

# Learnings

## Basics if quantum mechanics
We went through the fundamentals of quantum mechanics, understanding everything in the language of linear algebra. We studied unitary time evolution under the Hamiltonian. We also learnt about Hermitian operators, and the relevance of their eigenvalues and eigenvectors, and commutativity.
We also understood the idea of measurement in terms of projection operators.

## Quantum circuits
* We started with the simplest quantum system, the qubit which exhibits two states $|0\rangle$ and $|1\rangle$
* We studied the basic unitary transforms like the identity, pauli gates, hadamard transform and rotations on the Bloch sphere
* We then proved that any one qubit gate can be approximated to arbitary accuracy using H, X, T and S gates
* We took the CNOT gate as the fundamental unit of extension to more than one qubits
* We then proved the constructability of all multi-qubit gates using CNOTs and single qubit gates
* We went on to find constructions for multi-qubit controlled gates using auxiliary qubits
* We understood the principle of delayed measurement and measurment in different basis
* We constructed some basic quantum circuits like swap, modular addition, comparison, subtraction, shift etc.

## Quantum Information and Encryption
* We studied about the no-cloning theorem
* We understood about quantum indistinguishability. We proved its equivalence with the no-cloning theorem. We also studied applications of this such as in quantum verification
* We understood the use of entanglement in quantum teleportation and superdense coding

## Basic themes in quantum algorithms
* Construction of states using gates, arbitary rotation and measurement. Construction of Bell, W and GHZ states
* Distinguishing unitaries. Using controlled gates and kickback for finding global phase
* Employing phase kickback of the X gate on auxiliary $\frac{|0\rangle - |1\rangle}{\sqrt{2}}$ to interconvert phase and value oracles
* Construction of oracles based on some classical operations
* Construction of superposition using H gate. The parallel processing power of quantum circuits
