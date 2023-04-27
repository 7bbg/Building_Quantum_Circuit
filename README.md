# Building_Quantum_Circuit
To make the x gates sits in the first moment and all hadamard gates [1] go into the next moment

1) A Hadamard gate is a quantum logic gate that acts on a single qubit. It is one of the most important gates in quantum computing, as it is used to create superposition states, which are essential for many quantum algorithms.
2)Quantum circuit are collection of moment were each moment contains operations of the qubits image{}.

![image](https://user-images.githubusercontent.com/104602972/232634476-6435db3c-4964-41a9-9588-3ee9e933dbd6.png)
image source(https://quantumai.google/static/cirq/images/CircuitMomentOperation.png)

### The Hadamard gate can be represented by the following matrix:

H = 1/sqrt(2) * [[1, 1], [1, -1]]
This matrix can be interpreted as follows:

If the qubit is in the state |0⟩, then the Hadamard gate will transform it into the state (|0⟩ + |1⟩)/√2.
If the qubit is in the state |1⟩, then the Hadamard gate will transform it into the state (|0⟩ - |1⟩)/√2.
In other words, the Hadamard gate puts the qubit into a superposition of the |0⟩ and |1⟩ states.

The Hadamard gate has many important properties. For example, it is its own inverse, which means that applying it twice will restore the qubit to its original state. It is also a unitary gate, which means that it preserves the overall probability of a state.

The Hadamard gate is used in many quantum algorithms, including Shor's algorithm for factoring integers and Grover's algorithm for searching unsorted databases. It is also used in quantum error correction, which is essential for building reliable quantum computers.

The Hadamard gate is a powerful tool that can be used to perform many different tasks in quantum computing. It is one of the most important gates in quantum computing, and it will play a key role in the development of quantum computers.
