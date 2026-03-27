This project explores the use of machine learning models to rapidly infer plasma parameters from Thomson scattering spectra. Traditional inversion methods are computationally expensive and time-consuming, motivating the use of neural networks as a fast and scalable alternative.

The primary goal of this work is to evaluate how effectively neural networks — especially transfer learning approaches — can predict key plasma properties such as electron density and temperature from spectral data.
Objectives:
1. Develop neural network models to predict plasma parameters from spectra (far more efficient than least-squares fitting)
2. Compare performance between:
- Models trained on synthetic data
- Models trained on experimental data
- Transfer learning approaches combining both
- Evaluate model accuracy and generalization across regimes
- Analyze performance differences in collective vs. non-collective scattering regimes


This project was designed to replicate and explore results presented in the following paper:
Machine learning for fast inversion of Thomson scattering spectra
https://iopscience.iop.org/article/10.1088/1361-6463/ad89d6

While the referenced work utilizes a significantly larger synthetic dataset (~10,000 samples), this project investigates similar methods under more constrained conditions, using datasets of ~1,300 samples each. This allows for analysis of how dataset size impacts model performance, particularly in transfer learning scenarios.
