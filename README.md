# Privacy-Preserving Medical Image Analysis

An implementation of a privacy-preserving medical image analysis system combining **Federated Learning (FL)** with **Homomorphic Encryption (HE)**.

## Overview

This project explores how medical image analysis can be performed while reducing the need to expose sensitive medical data.

The implementation combines:

- **Federated Learning** for distributed model training
- **Homomorphic Encryption** for protecting data during computation
- **Medical image analysis** using a brain tumor image dataset
- Encryption and decryption components implemented in Python
- Machine learning experiments on encrypted and unencrypted data

The project includes the implementation, preprocessing notebooks, encryption components, and experimental outputs used to investigate privacy-preserving medical image analysis.

## Project Structure

```text
.
├── DataPreprocessingAndMLModelRun.ipynb
├── HomomorphicEncryptionOfDataset.ipynb
├── ModelOnUnencryptedData.ipynb
├── ImageCryptography.py
├── ModularArithmetic.py
├── Paillier.py
├── RabinMiller.py
├── public_key.txt
├── Encrypted output.png
├── Unencryped output.png
├── loglosspng.png
├── .gitignore
└── .gitattributes
```

## Main Components

### Federated Learning

The project investigates a distributed learning setup where model training can be performed without directly centralizing the underlying medical image data.

### Homomorphic Encryption

Homomorphic encryption components are implemented in Python to support computation over protected data.

The repository includes an implementation of the **Paillier cryptosystem**, together with supporting modular arithmetic and primality-testing components.

### Medical Image Analysis

The experiments use brain tumor medical images to investigate machine learning on protected data.

The original datasets are **not included in this repository** because of their size. They must be obtained separately before reproducing the experiments.

## Technologies

- Python
- Jupyter Notebook
- Federated Learning
- Homomorphic Encryption
- Paillier Cryptosystem
- Medical Image Analysis
- Machine Learning

## Notebooks

| Notebook | Purpose |
|---|---|
| `DataPreprocessingAndMLModelRun.ipynb` | Data preprocessing and machine learning experiments |
| `HomomorphicEncryptionOfDataset.ipynb` | Encryption-related experiments |
| `ModelOnUnencryptedData.ipynb` | Experiments using unencrypted data |

## Encryption Implementation

The repository contains Python implementations for the cryptographic components:

- `Paillier.py` — Paillier homomorphic encryption
- `ModularArithmetic.py` — modular arithmetic operations
- `RabinMiller.py` — primality testing
- `ImageCryptography.py` — image encryption-related functionality

## Experimental Outputs

The repository includes selected output files generated during the experiments, including:

- Encrypted and unencrypted image examples
- Model loss visualization

## Dataset

The medical image datasets used during development are intentionally excluded from this repository.

The `.gitignore` file excludes the local dataset directories:

```text
Brain_Tumor_Dataset/
encrypted-images/
```

To reproduce the experiments, obtain the required dataset separately and place it in the expected directory structure.

## Purpose

The project demonstrates an implementation-oriented approach to combining privacy-preserving techniques with medical image analysis, with a focus on the practical use of **federated learning and homomorphic encryption**.

## Author

**Raisul Kabir News**
