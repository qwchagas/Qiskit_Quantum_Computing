### Qiskit, Implementations and Algorithms


#### Algorithms
1) [Deutsch-Jozsa's algorithm](https://github.com/qwchagas/qiskit/blob/master/algorithms%20and%20transpile/deutsch_jozsa_algorithm_transpile.ipynb): here we have a general implementation of Deutsch-Jozsa's algorithm that uses a phase oracle constructed by a diagonal function and the transpile. We avoid and abstract the construction of the oracle in order to get this general implementation.

2) [Grover's algorithm](https://github.com/qwchagas/qiskit/blob/master/algorithms%20and%20transpile/grover_algorithm_transpile.ipynb): similar to the Deutsch-Jozsa's algorithm, we have the construction of the diffusion and oracle operators based on diagonal functions. Again, it's more abstract because we avoid touching each part of the circuit, but we can easily generalize this algorithm, even for multiple marked elements.

3) [Bernstein-Vazirani algorithm](https://github.com/qwchagas/qiskit/blob/master/algorithms%20and%20transpile/bernstein-vazirani_algorithm_transpile.ipynb): this algorithm explores the power of hamadard transformation and we applied the same techniques here, phase oracle based on a diagonal function that constructs our operator.

#### Operations
1) [Increment](https://github.com/qwchagas/qiskit/blob/master/operations/increment.ipynb): generalized increment operation
2) [Decrement](https://github.com/qwchagas/qiskit/blob/master/operations/decrement.ipynb): generalized decrement operation


#### Quantum Walks

#### Miscellaneous

1) [IBM Quantum Challenge 2020](https://github.com/qwchagas/qiskit/blob/master/misc/challenge4_circuit_optimization_ibm.ipynb): I explored the sensibility of the transpile function adding up a global phase to a diagonal operator in order to lower the number of gates. My best score was 50.

