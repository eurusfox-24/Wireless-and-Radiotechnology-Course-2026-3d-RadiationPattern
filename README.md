# Wireless-and-Radiotechnology-Course-2026-3d-RadiationPattern
> 3D Radiation Pattern Visualization using MATLAB

## Student Information
 
- **Student ID:** s2312638

---

## Aim
To generate and visualize a **3D radiation pattern** using spherical coordinates in MATLAB by converting them into Cartesian coordinates.

---

## Description
This program takes user-defined angular ranges for **theta (θ)** and **phi (φ)** in degrees.  
It computes the radiation field pattern, converts spherical coordinates to Cartesian coordinates using `sph2cart`, and displays the result as a 3D mesh plot.

---

## Input Parameters
After running the program, MATLAB will ask for the following inputs:

- Lower bound of theta (degrees)
- Upper bound of theta (degrees)
- Lower bound of phi (degrees)
- Upper bound of phi (degrees)
- Field pattern: `E(THETA,PHI)`
- Field pattern label: `P(THETA,PHI)`

### Sample Inputs Used
```text
Theta lower bound = 0
Theta upper bound = 360
Phi lower bound   = 0
Phi upper bound   = 360
E(THETA,PHI) = 1
P(THETA,PHI) = 1
