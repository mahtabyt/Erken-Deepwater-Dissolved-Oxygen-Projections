# Deepwater Dissolved Oxygen Model Outputs

## Overview

This repository provides selected outputs from a deepwater dissolved oxygen (DO) modelling framework. The datasets represent simulated oxygen profiles during the **summer stratified period**.

Each file contains deepwater DO concentrations below the stratified layer. Values outside the summer stratified period are assigned **NaN** to indicate periods not included in the analysis.

## Model Simulations

All datasets were generated using the **GOTM-DO** modelling framework. Files include simulations for:

* Historical conditions (**his**)
* Multiple future climate scenarios (**RCPs**)

The applied climate scenario is specified directly in the filename.

## Climate Model Forcing

Simulations were forced using bias-corrected climate projections from ISIMIP2b Global Climate Models (GCMs). The driving GCM is indicated in each filename:

* GFDL
* HadGEM
* IPSL
* MIROC

Each file therefore represents one specific combination of climate forcing and emission scenario.

## Model Parameterisation

All datasets shown here correspond to a single calibrated parameter configuration of the DO model:

* Vertical respiration parameter: **Jv = 0.2 g m⁻³ d⁻¹**
* Sediment oxygen demand parameter: **Ja = 0.5 g m⁻² d⁻¹**

## Data Structure

* Time series of deepwater dissolved oxygen concentrations
* Values limited to the summer stratified season
* Non-stratified periods represented as **NaN**

## Related Publication

A full description of the deepwater oxygen modelling framework, calibration procedure and methodological details can be found in:

Yaghouti et al. (2026)
https://www.sciencedirect.com/science/article/pii/S1364815226000885

## Usage

These datasets are shared to support transparency, reproducibility and reuse in studies investigating climate-driven changes in lake oxygen dynamics.
