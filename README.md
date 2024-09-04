# Quantum state and process tomography

The notebook contains an array of Python functions and routines needed to both simulate and analyse real-world data, when performing both single- and two-qubit quantum state tomography, as well as both standard single- and two-qubit quantum process tomography (using the $\chi$ process matrix formalism).

The notebook is highly commented, with markdown explanations of almost every code block.

## Requirements

The notebook was tested using Visual Studio Code on MacOS in a custom environment, with the following packages installed using conda

* python=3.10
* ipykernel=6.28
* numpy=1.26
* scipy=1.12
* matplotlib=3.9

## Further development

* Compute the process and gate fidelity, given the experimental $\chi$ and a unitary representing an ideal version of the process.

## Issues

* Check whether the $\chi$ matrix needs to be unitary, and investigate under what conditions finding the Kraus operators, given $\chi$, will fail (as encapsulated in the `compute_kaus_operators` function).

## License

This project was written for use at Fermilab; the [Apache License 2.0](https://github.com/bornman-nick/quantum-state-and-process-tomography/blob/main/LICENSE) license applies.
