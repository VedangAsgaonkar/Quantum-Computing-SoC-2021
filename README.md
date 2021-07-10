# Quantum-Computing-SoC-2021

# Learnings

## Basics if quantum mechanics
We went through the fundamentals of quantum mechanics, understanding everything in the language of linear algebra. We studied unitary time evolution under the Hamiltonian. We also learnt about Hermitian operators, and the relevance of their eigenvalues and eigenvectors, and commutativity.
We also understood the idea of measurement in terms of projection operators.

## Quantum circuits
* We started with the simplest quantum system, the qubit which exhibits two states <img src="https://render.githubusercontent.com/render/math?math=|0\rangle"> and $|1\rangle$
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

## Quantum Fourier Transform
* We studied the discrete fourier transform, its inverse. We understood the quantum algorithm for it, which is more efficient than the classical FFT
* We understood the phase finding algorithm for finding phase of eigenvalues. We studied about the number of qubits neede for a given accuracy threshold. We also studied, how a superposition of eigenvectors can be used for this algorithm
* We used phase finding for the order finding algorithm by using an oracle which performs the modular exponentiation in terms of qubits. We found the eigenvectors and eigenvalues of such an oracle in terms of the order. We then supplied a superposition of these eigenvectors i.e. the zero state and use phase estimation to find the order in constant time
* We then employed order finding for the Schor's algorithm, to find prime factors
* We generalised this method to the period finding problem. We also generalised to functions of higher dimensions by solving the discrete logarithm problem

## Quantum Search
* We understood the idea of oracles, and the fact that verification is not the same as solving
* We used Grover iterations to search through unstructured databases with a quadratic speed-up
* We understood the Grover's algortihm in terms of rotation in a space spanned by the uniform superposition of solutions and non-solutions
* We employed phase estimation on each Grover unit to find the number of solutions in constant time i.e. quantum counting
* We understood the idea of quantum simulation, and how the Grover's search can be understood as finding a suitable Hamiltonian
