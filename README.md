# Aerospace-Technology-Lab

# 3D Printing of Lunar Regolith Simulant (LHS-1) via Vat Photopolymerization

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Language](https://img.shields.io/badge/Language-Italian%20%7C%20English-lightgrey.svg)](#translation-notice)

Repository containing the laboratory report, experimental datasets, image processing routines, and mechanical characterization for the **Laboratorio di Tecnologie Aerospaziali** course at **Politecnico di Milano** (A.Y. 2024/2025).

---

## 🌐 Language & Translation Notice

> **Note on Translation:**  
> The original technical report was drafted and submitted in Italian (`Relazione_gruppo5.pdf`). The English translation (`Report_group5_CaporizziFA.pdf`) was generated using Artificial Intelligence (LLM) and subsequently **manually reviewed, validated, and refined** to ensure technical accuracy, consistent aerospace engineering terminology, and contextual alignment with laboratory standards.

---

## 📌 Project Overview

The objective of this laboratory was to evaluate the feasibility, criticalities, and mechanical performance of stereolithography/vat photopolymerization 3D printing using a **lunar regolith simulant (LHS-1)** mixed with a photopolymer resin. 

The investigation covered CAD design, slicing, RAMS process reliability, microscopic defectology/image processing, and destructive mechanical testing across green and sintered ceramic specimens.

---

## 🔬 Key Methodologies & Analyses

### 1. Material Characterization & R.A.M.S. Analysis
* **Slurry Composition:** Custom photocurable resin (30 wt%) loaded with **LHS-1 lunar regolith simulant** (70 wt%), primarily composed of anorthosite (74.4%) and glass-rich basalt (24.7%).
* **Particle Size Discrepancy:** Identified a significant deviation from manufacturer specs, with 100% of particles under $8.71\,\mu\text{m}$ (vs. expected $< 12\%$), causing increased specific surface area, elevated slurry viscosity, and UV scattering.
* **R.A.M.S. Evaluation (Elegoo Mars 4 DLP):**
  * **Reliability:** Optimized exposure time (15 s) and moderate lift/retract speeds (40 / 80 mm/min) to prevent mechanical arm wear.
  * **Availability:** Lifting distance (10 mm) and resting times between layers (21 s total).
  * **Maintainability & Safety:** Z-axis alignment stability and UV source power control (18 W).

### 2. Microscopic Quality & Defectology
* **Dimensional Shrinkage:** Calibrated calipers and SEM observations measured non-isotropic shrinkage post-debinding and sintering (e.g., volumetric shrinkage of $\approx 37.1\%$ from green to ceramic).
* **Layer & Pore Segmentation:** MATLAB-based automated image processing evaluated:
  * Layer height: $28.84 \pm 0.33\,\mu\text{m}$ (nominal $30\,\mu\text{m}$).
  * Grain growth ($0.93\,\mu\text{m} \rightarrow 0.98\,\mu\text{m}$) and void enlargement ($0.50\,\mu\text{m} \rightarrow 0.76\,\mu\text{m}$) due to particle coalescence.
* **Ishikawa Root-Cause Defect Analysis:** Identified crack propagation mechanisms along gyroid hole intervals driven by residual stress concentration around large un-sintered grains ($> 13.7\,\mu\text{m}$).

### 3. Mechanical Characterization
* **Monotonic Compressive Strength (ASTM C1424-25):** Conducted on gyroid lattice cylinders (60% infill) using an MTS 858 Mini Bionix II test frame.
  * Ultimate Compressive Strength: **109.87 MPa** and **153.04 MPa**.
  * Linear elastic stiffness: $7.29\text{ kN/mm}$ and $10.97\text{ kN/mm}$.
* **Flexural Strength (ASTM C1161-18):** Three-point bending setup tested sintered rectangular bars to brittle fracture:
  * Specimen 1: **134.43 MPa**
  * Specimen 2: **147.94 MPa**
  * Specimen 3: **114.93 MPa**

---

## 🛠️ Software & Tools Used

* **CAD & Slicing:** Autodesk Fusion®, Chitubox®
* **Microscopy & Image Analysis:** Optical Microscope, Scanning Electron Microscope (SEM), MATLAB® Image Processing Toolbox, ImageJ®
* **Mechanical Testing Software:** MTS 858 Mini Bionix II® data acquisition system

---

## 👥 Authors (Group 5)

* **Francesco Alessandro Caporizzi**
* **Lucrezia Finelli**
* **Davide Grisendi**
* **Mario Guida**
* **Marco Lanzani**
* **Paola Mansueti**
* **Ettore Manzini**
* **Luca Marchini**
* **Francesco Mariotti**
* **Francesco Martinelli**
* **Samuele Micotti**
* **Maria Chiara Moltrasio**

**Academic Supervisor:** Prof. Antonio Mattia Grande  
*Department of Aerospace Science and Technology (DAER), Politecnico di Milano.*
