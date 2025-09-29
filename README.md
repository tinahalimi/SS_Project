# DOA Estimation with ESPRIT (LS & TLS) – MATLAB

## Overview
This repository contains my *Signals and Systems* course project at Sharif University of Technology. The project implements **ESPRIT** algorithms for **Direction of Arrival (DOA)** estimation of narrowband sources received by a uniform linear array. Two estimation pipelines are included:

- **LS–ESPRIT**: classical least-squares solution of the shift-invariance equations.  
- **TLS–ESPRIT**: total least-squares variant that accounts for noise and errors in both sides of the equations.  

The accompanying report explains array and steering-vector modeling, covariance estimation, eigen-decomposition, signal/noise subspace separation, solving the ESPRIT invariance relation, and converting eigenvalues to arrival angles.

---

## File Structure
- `main.m` — Reproducible demo: generates/simulates array data and runs LS-ESPRIT.  
- `TLS.m` — Functions for TLS-ESPRIT (building the partitioned subspaces and solving the TLS problem).  
- `Report.pdf` — Full project report (in Persian): theory, derivations, assumptions, pros/cons, and worked examples.  

---

## Author
- **Tina Halimi**  
- **Kimia Ramezan**
- **Mahdi Zinati**  
