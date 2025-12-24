# Benchmark-of-Optimizers-in-VQE

## ⚠️ Research Code Disclaimer
*This repository contains the experimental code used for the manuscript "Benchmarking Classical Optimizers for VQE in NISQ Devices". It was developed for rapid prototyping and data collection in a scientific research context.*

## 📌 Project Overview
This project investigates the performance of classical optimization algorithms (**COBYLA, ADAM, PSO**) when applied to the Variational Quantum Eigensolver (VQE) for simulating the $H_2$ molecule.

The study is divided into two simulation regimes to isolate the effects of hardware noise on optimizer convergence:
1.  **Ideal Baseline (Noise-Free):** Statevector simulations to validate theoretical convergence.
2.  **NISQ Simulation (Noisy):** Simulations using **Qiskit Aer** noise models to mimic real quantum hardware conditions (decoherence and gate errors).

Authored by Carlos Esteves | FAPESPA Research Fellow
