# Determination of Fringe Pattern and Shape in Double Slit Experiment by Analytical Methods

This project presents an analytical study of fringe formation in Young’s Double Slit Experiment, where the **inclination of the screen** is treated as a controllable parameter.

---

## Overview

This project explores a modified version of Young’s Double Slit Experiment in which the observation screen is inclined at an angle (ψ).

Using an analytical approach, the fringe patterns are derived and interpreted as **loci of constant path difference**. These loci form **conic sections** — ellipses, parabolas, or hyperbolas — depending on system parameters.

The simulation visualizes these fringes as contour-like curves, revealing the geometric structure underlying wave interference.

---

## Input Parameters

The program requires the following inputs:

- **d** : Slit separation (in mm)  
- **λ (lambda)** : Wavelength of light (in nm)  
- **D** : Distance to screen (in m)  
- **ψ (psi)** : Inclination angle of the screen (in degrees)  

---

## Output

- A graphical plot of **bright fringes** (constructive interference)  
- Fringe curves obtained from the analytical equation  
- Color of fringes varies with the input wavelength  

---

## Method

The program evaluates an equation of the form:

F(x, y, n) = 0

where:
- *(x, y)* are Cartesian coordinates  
- *n* represents the fringe order  

To maintain visual clarity, the fringe orders are chosen as:

n ∈ {2³, 3³, 4³, ..., 14³}

This cubic spacing ensures better separation between curves and improves interpretability of the plot.

---

## How to Run

1. Run the Python script  
2. Enter the required input values when prompted  
3. The fringe pattern will be displayed in a plot window  

---

## Notes

- Assumes ideal conditions (equal intensity fringes)  
- Only fringes of total constructive interference are plotted  
- Based on analytical approximations (including small-angle assumptions)  

---

## Acknowledgment

Thank you for exploring this project!
