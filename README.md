# Acoustic Tactile Plate: Impact Source Localization

This Numerical Methods project (conducted at **ESPCI Paris - PSL**) focuses on **acoustic tactile conversion**, a robust alternative to classic capacitive touch technologies. The system relies on the physical analysis of mechanical bending waves propagating through a rigid solid plate following a localized impact.

## 🚀 Project Overview
The core objective is to accurately reconstruct the $(x, y)$ spatial coordinates of a physical impact on a surface by processing the time-domain signals recorded by only **three piezoelectric sensors**.

### Key Features:
* **Physical Modeling:** Simulation of bending wave propagation and vibrations within a complex reverberant medium.
* **Signal Processing:** Time Difference of Arrival (TDOA) and phase analysis of the raw acoustic wavefields.
* **Numerical Optimization:** Inverse problem-solving using minimization algorithms (via `scipy.optimize`) to pinpoint the precise location of the source impact.
* **Robustness & Error Mapping:** Evaluation of system performance under noisy conditions or frequency perturbations, with full spatial error mapping to identify local "shadow zones".

## 🛠 Tech Stack
* **Language:** Python
* **Scientific Libraries:** NumPy, SciPy (Signal & Optimize)
* **Visualization:** Matplotlib (GridSpec, Patches)

## 👥Authors 
* Raphael Törnqvist (ESPCI Paris - PSL)
* Arthur Quairel (ESPCI Paris - PSL)
