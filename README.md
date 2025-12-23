# Crack-Formation-PV-Modules
ANSYS + EL-based stress and crack analysis in c-Si PV modules (Helmholtz Erlangen project)
# Crack Formation Analysis in c-Si PV Modules

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Problem

Mechanical stress from different clamping configurations can induce cracks in c-Si PV cells and reduce module efficiency over time.[file:16]

## Methods

- **ANSYS simulations** of mechanical stress under multiple clamping positions.
- **EL imaging** to identify stress hotspots and crack patterns.
- **Data analysis** using Python and Excel on displacement, EL, and I‑V datasets.[file:16]

## Repository Structure

- `notebooks/` – Jupyter notebooks performance analysis.
- `data/` – Example or synthetic datasets for stress, EL intensity, and I‑V curves.
- `requirements.txt` – Python dependencies to run the notebooks.

## Quick Start
git clone https://github.com/Fiza-13150698/Crack-Formation-PV-Modules
cd Crack-Formation-PV-Modules
pip install -r requirements.txt
jupyter notebook notebooks/stress_analysis.ipynb

