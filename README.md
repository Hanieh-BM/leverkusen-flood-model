# Leverkusen Flood Model (July 2021)
### Custom 2D Cellular Automata Simulation

This repository contains a Python-based **Cellular Automata (CA)** model developed to simulate the devastating 2021 flood event in **Leverkusen-Opladen, Germany**. 

## 🌊 Project Overview
This study presents the iterative development of a flood inundation model, transitioning from a simple explicit scheme to a robust **implicit-iterative physics engine**. The model was calibrated against official gauge records, achieving a modeled peak of **4.65m** (vs. 4.66m observed).

### Key Features:
* **Physics Engine:** Stable implicit-iterative WSE-driven flow.
* **Initial Conditions:** Observation-based baseflow (1.23m) with a dedicated spin-up stabilization period.
* **Hydrological Processes:** Intelligent recession mechanism, LULC-based infiltration, and irreversible sink boundaries.
* **Validation:** Comprehensive diagnostic validation including mass balance and instability seismograph analysis.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:** NumPy, SciPy, Rasterio, Matplotlib
* **Data Sources:** 1m DTM, LULC maps, and DWD RADKLIM precipitation data.

## 📊 Key Results
* **Accuracy:** Excellent agreement at the Opladen gauge (1cm margin).
* **Efficiency:** Capable of simulating a 40-hour storm event in ~2-3 hours on standard hardware.
* **Diagnostic Utility:** Successfully identified urban hydraulic uncertainties (e.g., pluvial/sewer influences at Schöllerstraße).

---
**Author:** Hanieh BaradaranMohammadi  
**Supervisors:** Prof. Dr. Antara Dasgupta, Paula Wessling da Silva, Eva-Lotte Schriewer  
**Institution:** Integrated Master Project - From Maps to Models (Summer Semester 2025)
