# 🌊 Ekman Effect – Wind & Surface Current Analysis in the Gulf of Trieste

## Overview

Analysis of wind forcing and surface currents in the Gulf of Trieste to assess consistency with Ekman transport theory.

The project combines exploratory data analysis with Bayesian parameter estimation via Markov Chain Monte Carlo (MCMC), providing both model fitting and uncertainty quantification.

---

## Dataset

CSV time series including:

- Wind speed and direction  
- Eastward and Northward surface current components measured by the VIDA oceanographic buoy (Marine Biology Station Piran)

Data were collected in the Northern Adriatic Sea.

---

## Analysis Workflow

### 1. Exploratory Data Analysis

- Visualization of wind and current time series  
- Reconstruction of current magnitude and direction from vector components  
- Angular deviation analysis between wind and surface current  
- Statistical characterization of current deflection patterns  

### 2. Bayesian Modeling

- Parametric model for the wind–current directional relationship  
- Likelihood definition and prior specification  
- Bayesian parameter estimation  
- MCMC sampling using `emcee` (affine-invariant ensemble sampler)  
- Posterior analysis and uncertainty quantification  

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- emcee  
- Jupyter Notebook  

---

## Skills Demonstrated

- Time-series analysis and preprocessing  
- Vector field reconstruction and directional statistics  
- Scientific data visualization  
- Bayesian inference and probabilistic modeling  
- MCMC sampling and posterior analysis  
- Quantitative parameter estimation with uncertainty propagation  
- Reproducible computational workflow  
