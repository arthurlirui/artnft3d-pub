# ArtNFT3D
### The Integration of Photo-realistic 3D Reconstruction and NFT 

![Project Logo](artnft3d-logo.jpg)

## Introduction

This project focuses on integrating **3D Reconstruction** technology with **NFT** for secure, decentralized, and verifiable 3D data management. Our system leverages the power of blockchain to ensure the integrity and traceability of 3D models, while utilizing advanced algorithms for precise and efficient 3D reconstruction.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture Overview](#architecture-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Accurate 3D Reconstruction**: Uses state-of-the-art algorithms to generate 3D models from 2D images or sensor data.
- **Blockchain Security**: Securely store and verify 3D data using blockchain technology to ensure data immutability and transparency.
- **Decentralized**: The system is fully decentralized, ensuring no single point of failure and providing greater security and reliability.
- **Tamper-proof 3D Models**: Each 3D model is hashed and stored on the blockchain, allowing for verification of authenticity.
- **Efficient Processing**: Optimized for performance with minimal computational overhead.
- **Interoperability**: Supports multiple formats for 3D model input/output (e.g., OBJ, STL, PLY).

## Technologies Used

- **3D Reconstruction**: 
  - Gaussian-splatting
  - NeuS
  - OpenCV
  - Meshroom
  - COLMAP
  - PCL (Point Cloud Library)

- **Blockchain**: 
  - Ethereum Smart Contracts (Solidity)
  - IPFS (InterPlanetary File System)
  - Web3.js for blockchain integration

- **Programming Languages**:
  - Python
  - C++
  - Move (for Aptos's Move Langurage)
  - Solidity (for smart contracts)
  - JavaScript (for frontend interaction)

## Architecture Overview

```mermaid
graph LR
    A[Image / Sensor Data] --> B[3D Reconstruction Algorithm]
    B --> C[3D Model]
    C --> D[Blockchain Storage]
    D --> E[Verification]
    F[User] --> E

