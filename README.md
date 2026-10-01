# An Advanced Data Fabric Architecture Leveraging Homomorphic Encryption and Federated Learning

Implementation and experimental code for an advanced data fabric architecture leveraging **homomorphic encryption** and **federated learning** for privacy-preserving medical image analysis.

## Overview

This repository contains the implementation and experimental notebooks developed for the thesis:

> **An Advanced Data Fabric Architecture Leveraging Homomorphic Encryption and Federated Learning**

The work explores privacy-preserving machine learning for medical image analysis by combining **federated learning** with **homomorphic encryption**. The repository includes code for data preprocessing, model experimentation, image cryptography, and supporting cryptographic operations.

## Repository Contents

| File | Description |
|---|---|
| `DataPreprocessingAndMLModelRun.ipynb` | Data preprocessing and machine-learning experimentation |
| `HomomorphicEncryptionOfDataset.ipynb` | Experiments involving homomorphic encryption of the dataset |
| `ModelOnUnencryptedData.ipynb` | Model experimentation using unencrypted data |
| `ImageCryptography.py` | Image-related cryptographic operations |
| `Paillier.py` | Paillier cryptosystem implementation |
| `RabinMiller.py` | Rabin–Miller primality-testing implementation |
| `ModularArithmetic.py` | Supporting modular arithmetic operations |
| `public_key.txt` | Public-key material used by the experiments |
| `Encrypted output.png` | Example encrypted-image output |
| `Unencryped output.png` | Example unencrypted-image output |
| `loglosspng.png` | Experimental model/loss visualization |

## Methodology

The implementation investigates a privacy-preserving workflow for medical image analysis incorporating cryptographic protection and federated learning.

The repository includes experimental components for:

- Medical image data preprocessing
- Machine-learning model experimentation
- Federated learning
- Homomorphic encryption
- Image encryption and decryption
- Paillier cryptosystem operations
- Modular arithmetic and primality testing
- Comparison of encrypted and unencrypted image processing

## Dataset

The original development repository contained medical image datasets and generated encrypted-image data. These large datasets are **not included in this repository** to keep the GitHub repository lightweight.

The notebooks and scripts therefore require the appropriate dataset files to be obtained and configured separately before reproducing the experiments.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/RaisulKabir27/Advanced-Data-Fabric-Architecture.git
cd Advanced-Data-Fabric-Architecture
```

### 2. Install dependencies

The exact dependencies may vary by notebook or experiment. Install the Python packages required by the corresponding notebook/script before execution.

### 3. Prepare the dataset

Obtain the required medical image dataset separately and place it in the directory structure expected by the notebooks.

### 4. Run the experiments

The main experimental workflow can be explored through:

```text
DataPreprocessingAndMLModelRun.ipynb
HomomorphicEncryptionOfDataset.ipynb
ModelOnUnencryptedData.ipynb
```

The Python cryptographic modules can also be used independently or together with the notebooks.

## Research Focus

- Privacy-Preserving Machine Learning
- Federated Learning
- Homomorphic Encryption
- Medical Image Analysis
- Applied Cryptography
- Secure Data Processing

## Notes

This repository contains research and experimental code associated with the thesis work. Dataset files are intentionally excluded from the repository.

## Author

**Raisul Kabir News**

## Citation

If you use this implementation or build upon this work, please cite the associated thesis/research work:

> **An Advanced Data Fabric Architecture Leveraging Homomorphic Encryption and Federated Learning**
