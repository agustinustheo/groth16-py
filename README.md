# Groth16-py

A Python implementation of the Groth16 zero-knowledge proof system, a key algorithm for efficient and private verification of computational statements.

## References

- [On the Size of Pairing-based Non-interactive Arguments](https://eprint.iacr.org/2016/260.pdf)
- [RareSkills: Groth16 Zero Knowledge Proofs](https://www.rareskills.io/post/groth16)
- [Groth16: A Compact and Efficient zk-SNARK](https://kayleegeorge.github.io/math110_WIM.pdf)

## Overview

This repository contains a Jupyter notebook implementation of the Groth16 algorithm, which is widely used in zero-knowledge proof systems like zk-SNARKs. The implementation demonstrates:

- Conversion from R1CS (Rank-1 Constraint System) to QAP (Quadratic Arithmetic Program)
- Complete trusted setup with alpha, beta, gamma, and delta parameters
- Proof generation with zero-knowledge properties through randomization
- Verification using bilinear pairings

## Key Features

- Full implementation of the Groth16 algorithm in Python
- Step-by-step demonstration in Jupyter notebook format
- Uses py_ecc for elliptic curve operations on the bn128 curve
- Includes randomization techniques for zero-knowledge properties

## Requirements

- Python 3.11+
- py_ecc library for elliptic curve operations
- numpy==1.26.0
- Jupyter notebook environment

## Getting Started

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install py_ecc numpy==1.26.0 jupyter
   ```
3. Open and run the `groth16.ipynb` notebook to see the implementation in action

## About

![RareSkills Logo](https://www.rareskills.io/wp-content/uploads/2024/08/og-image-rareskills.png)

This implementation was created as part of a project for [RareSkills](https://www.rareskills.io/), an advanced blockchain development bootcamp focusing on smart contract security and zero-knowledge proofs.

## License

See the [LICENSE](LICENSE) file for details.