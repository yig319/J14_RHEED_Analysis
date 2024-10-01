# RHEED Data Analysis for J14 Thin Film Growth Using PLD

This repository contains the scripts and documentation necessary to analyze Reflection High-Energy Electron Diffraction (RHEED) data collected during the growth of J14 thin films via Pulsed Laser Deposition (PLD). This analysis focuses on understanding the growth dynamics, surface morphology, and crystallinity of the J14 film through time-resolved RHEED measurements.

## Table of Contents
- [Project Overview](#project-overview)
- [RHEED Analysis Pipeline](#rheed-analysis-pipeline)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)

## Project Overview

In this project, we analyze RHEED patterns to monitor the layer-by-layer growth of J14 thin films synthesized using PLD. RHEED provides real-time insights into the surface structure of the thin film, offering critical information about the growth dynamics, crystalline quality, and roughness during deposition.

The J14 thin films in this study were grown under controlled conditions, using high-purity targets and specific growth parameters optimized for achieving epitaxial growth.

## RHEED Analysis Pipeline

This repository provides a framework for automating the analysis of RHEED data. The analysis pipeline includes the following steps:

1. **Preprocessing:**
   - **Spot Extraction:** Extract the RHEED spots from the full-view frame image.
   - **Normalization:** Normalizing intensity variations to improve comparability across frames.
   
2. **Pattern Recognition:**
   - **Spot Detection:** Detecting diffraction spots that correspond to different crystal planes.
   - **Intensity Mapping:** Analyzing the intensity of the diffraction spots over time to track the growth of atomic layers.

3. **Quantitative Analysis:**
   - **Oscillation Analysis:** Measuring intensity oscillations to estimate layer thickness and growth rates.
   - **Surface Roughness Evaluation:** Determining surface roughness from the streakiness of RHEED patterns.
   
4. **Data Visualization:**
   - **2D Visualization:** Visualization of RHEED intensity maps and growth dynamics over time.
   - **Surface Morphology:** Generation of heatmaps and surface models from RHEED data to understand surface evolution.

## Data

The RHEED data used in this analysis consist of a time series of diffraction patterns collected during the growth of J14 thin films. Each pattern corresponds to a snapshot of the surface structure during deposition. The data is too big for synced in GitHub repository, so datasets are available upon request.
