### Qiskit, Implementations and Algorithms


#### Algorithms
1) [Deutsch-Jozsa's algorithm](https://github.com/qwchagas/qiskit/blob/master/algorithms%20and%20transpile/deutsch_jozsa_algorithm_transpile.ipynb): here we have a general implementation of Deutsch-Jozsa's algorithm that uses a phase oracle constructed by a diagonal function and the transpile. We avoid and abstract the construction of the oracle in order to get this general implementation.
2) [Grover's algorithm](https://github.com/qwchagas/qiskit/blob/master/algorithms%20and%20transpile/grover_algorithm_transpile.ipynb): similar to the Deutsch-Jozsa's algorithm, we have the construction of the diffusion and oracle operators based on diagonal functions. Again, it's more abstract because we avoid touching each part of the circuit, but we can easily generalize this algorithm, even for multiple marked elements.
3) [Bernstein-Vazirani algorithm](https://github.com/qwchagas/qiskit/blob/master/algorithms%20and%20transpile/bernstein-vazirani_algorithm_transpile.ipynb): this algorithm explores the power of hamadard transformation and we applied the same techniques here, phase oracle based on a diagonal function that constructs our operator.
4) [QAOA + MaxCut](https://github.com/qwchagas/qiskit/blob/master/algorithms%20and%20transpile/qaoa_maxcut.ipynb): We've implemented the problem of max-cut using QAOA. Moreover, we've used the Pennylane package in order to obtain the ideal parameters for the problem.

#### Operations
1) [Increment](https://github.com/qwchagas/qiskit/blob/master/operations/increment.ipynb): we have a general increment operator, performing in arithmetic modulo N, and this is a very useful operation for Quantum Walks. Although, I will use this function in Quantum Walks, but in a controlled version.
2) [Decrement](https://github.com/qwchagas/qiskit/blob/master/operations/decrement.ipynb): here we find the decrement operator, performing in arithmetic modulo N, but in a optimized version, because we can group some X operators and we lower the number of gates here.

#### Quantum Walks

#### Miscellaneous

1) [IBM Quantum Challenge 2020](https://github.com/qwchagas/qiskit/blob/master/misc/challenge4_circuit_optimization_ibm.ipynb): I explored the sensibility of the transpile function adding up a global phase to a diagonal operator in order to lower the number of gates. My best score was 50.

2) [First Quantum Simulation in Qiskit](https://twitter.com/bochagas/status/1278707589916889089): Twitter post on how to build and run your first quantum program on IBM-Q and I explained each part of the code – in portuguese.

