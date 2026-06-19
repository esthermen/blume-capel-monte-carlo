# Blume-Capel Model Monte Carlo Simulation

Implementation of a Monte Carlo simulation of the two-dimensional Blume-Capel model using the Metropolis algorithm.

## Overview

The Blume-Capel model is an extension of the Ising model in which each lattice site can take three possible spin values:

S = {-1, 0, +1}

The Hamiltonian is given by:

H = -J Σ S_i S_j + Δ Σ S_i²

where Δ is the crystal field parameter controlling the density of vacancies.

## Features

- Two-dimensional square lattice
- Periodic boundary conditions
- Metropolis Monte Carlo updates
- Magnetization calculation
- Magnetic susceptibility calculation
- Temperature and crystal field sweeps
- Comparison with mean-field predictions

## Physics Background

This project investigates the phase diagram of the Blume-Capel model, including:

- Ferromagnetic and paramagnetic phases
- Second-order phase transitions
- Tricritical behavior
- Recovery of the Ising model in the limit Δ → -∞

## Implementation

Language: C++

Lattice size: 20 × 20

Algorithm: Metropolis Monte Carlo

Observables:
- Magnetization
- Magnetic susceptibility

## Documentation

A complete description of the theoretical background, numerical implementation and results is available in:

Blume_Capel_Report.pdf

## Authors

Esther Menéndez Ibáñez

[Nombre de tu compañero]
