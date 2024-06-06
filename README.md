# Average consensus with resilience and privacy guarantees without losing accuracy

This repository contains the implementation of the methodology proposed in the paper titled **"Average consensus with resilience and privacy guarantees without losing accuracy"**. This paper addresses the challenge of achieving private and resilient average consensus among a group of discrete-time networked agents without losing accuracy. To use this work please cite the following:

[TO_INSERT_BIBTEX_ENTRY]

## Overview

State-of-the-art solutions to attain privacy and resilient consensus often involve a trade-off between privacy and resilience, compromising on accuracy. Our work proposes a methodology that avoids these trade-offs, maintaining resilience, privacy, and accuracy simultaneously.

### Key Features

- **Resilient Consensus**: Our method maintains both resilience and accuracy without trade-offs, enabling agents to reach average consensus.
- **Privacy Preservation**: Inspired by differential privacy techniques, agents add noise to obscure their original state while maintaining the integrity of the consensus.
- **No Left-Eigenvector Computation**: Unlike many consensus methods, our approach does not require each agent to compute the left-eigenvector of the dynamics matrix associated with the eigenvalue of one.
- **Polynomial Time Complexity**: The proposed framework operates with a polynomial time complexity relative to the number of agents and the maximum quantity of allowed attacked agents.
- **Empirical Validation**: The efficacy of our method is demonstrated through empirical evidence and numerical outcomes.

## Installation

To run the code, you will need Python and the following dependencies:

- numpy
- functools
- matplotlib
- random
- math
- itertools
- scipy

You can install the dependencies using pip, for example:

```sh
pip install numpy scipy matplotlib
```

## Usage

1. **Clone the repository**:

```sh
git clone https://github.com/xuizy/Average_consensus_with_resilience_and_privacy_guarantees_without_losing_accuracy/
cd Average_consensus_with_resilience_and_privacy_guarantees_without_losing_accuracy
```

2. **Run the implementation**:

You can run the main nootebook to simulate the proposed consensus algorithm. The algorithm contains examples.

```sh
jupyter-notebook Average_consensus_with_resilience_and_privacy_guarantees_without_losing_accuracy.ipynb
```


## Results

The results of the simulation will be visualized using Matplotlib, showing the convergence of agent states to the average consensus while preserving privacy, resilience, and accuracy.

## Contribution

We welcome contributions to enhance the implementation and extend its capabilities. Please feel free to fork this repository and submit pull requests.

## License

This project is licensed under the Creative Commons Attribution (CC BY) License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact:

- [Guilherme Ramos](mailto:guilherme.ramos@tecnico.ulisboa.pt)
- [GitHub Profile](https://github.com/xuizy)
