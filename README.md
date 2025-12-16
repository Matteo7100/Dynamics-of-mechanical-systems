# Dynamics of Mechanical Systems – Harbour Crane Analysis

This repository contains the source code and documentation for the dynamic analysis of a harbour crane. The project focuses on modeling the mechanical system, deriving the equations of motion, and simulating its behavior using MATLAB.

---

## Overview

The primary goal of this project is to study the dynamics of a harbour crane system. The work involves defining the kinematic structure, applying dynamic principles to derive the governing equations, and performing numerical simulations to analyze the system's response under various conditions.

This repository serves as a digital companion to the detailed analysis provided in the project report.

---

## Repository Contents

The repository is structured as follows:

* **`yearwork_matlab.m`**
    The main MATLAB script containing the implementation of the dynamic model. It likely includes the definition of system parameters, derivation of equations (symbolic or numerical), and the simulation loop.

* **`structure_yw_mkr.mat`**
    A MATLAB data file (binary) containing pre-computed variables, structural parameters, or simulation results required by or generated from the main script.

* **`DYNAMICS_OF_MECHANICAL_SYSTEMS.pdf`**
    The full project report. It provides the theoretical background, mathematical derivation of the model (e.g., using Lagrange mechanics or Newton-Euler methods), and a discussion of the obtained results.

---

## Features

* **Dynamic Modeling:** Implementation of the mechanical equations governing the crane's motion.
* **Simulation:** Numerical integration of the equations of motion to visualize the system's behavior over time.
* **Data Analysis:** Use of MATLAB structures to handle system parameters and simulation data.

---

## Requirements

To run the code, you need:

* **MATLAB** (The code was developed and tested in a standard MATLAB environment).
* **Curve Fitting Toolbox** or **Symbolic Math Toolbox** (depending on the specific methods used in the `.m` file, though standard MATLAB is often sufficient).

---

## Usage

1.  Clone this repository or download the files to your local machine.
2.  Open **MATLAB** and navigate to the project folder.
3.  Ensure `structure_yw_mkr.mat` is in the same directory (or added to the MATLAB path).
4.  Run the main script:
    ```matlab
    yearwork_matlab
    ```
5.  Refer to `DYNAMICS_OF_MECHANICAL_SYSTEMS.pdf` for a detailed explanation of the theory and results.
