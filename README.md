# Emotion Recognition from Speech

Welcome to the Emotion Recognition from Speech project! This project implements the research paper titled "Automatic Speech Emotion Recognition Using Parallel Based Networks" published in MDPI Electronics.

## Overview
This project focuses on automatic speech emotion recognition (SER) using parallel based networks trained on the Ryeson Audio-Visual Dataset of Speech and Song (RAVDESS) dataset. The goal is to classify eight different emotions using a combination of CNN-based and attention-based networks running in parallel.

## Research Paper
The research paper titled ["Speech Emotion Recognition Based on Parallel CNN-Attention Networks with Multi-Fold Data Augmentation"](https://www.mdpi.com/2079-9292/11/23/3935) explores the implementation details and results of this project. It discusses the architecture, data augmentation techniques, and performance evaluation of the proposed models.

## Key Features
- Utilizes CNN-based and attention-based networks to model spatial and temporal feature representations.
- Augments training data using Additive White Gaussian Noise (AWGN), SpecAugment, Room Impulse Response (RIR), and Tanh Distortion techniques.
- Transforms raw audio data into Mel-Spectrograms as model input.
- Compares different architectures including parallel CNN-Transformer and parallel CNN-BLSTM-Attention networks.

## Getting Started
1. Clone this repository: `git clone <repository_url>`
2. Refer to the research paper for detailed implementation and experimentation details.
3. Explore the codebase to understand the implementation of parallel based networks for emotion recognition from speech.

## Usage
- Train and evaluate the implemented models on your own datasets.
- Experiment with different data augmentation techniques and network architectures to improve performance.
- Contribute to the project by extending the implemented models or proposing new techniques.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
Special thanks to the authors of the research paper for their valuable insights and contributions.
