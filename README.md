# ORION: Integrated Runtime Modeling for Predicting Deep Learning Training Time

<p align="center">
  <img src="assets/orion_logo.png" alt="ORION Logo" width="220"/>
</p>

ORION is an integrated runtime prediction framework that jointly models **GPU compute**,  
**CPU data preparation**, and **storage throughput** to accurately estimate the  
per-iteration training time of modern deep neural networks across diverse hardware  
configurations.

This repository includes:
- Scripts for **data generation** across CNN, MLP, and Transformer architectures
- Scripts for **RMSE evaluation**, including baseline comparisons
- Scripts for **unseen-GPU (LOGO) evaluation**
- Scripts for **reproducing all figures** included in the paper (ICPE 2026 submission)

---

## Installation

```bash
git clone https://github.com/genericgitrepos/ORION.git
cd ORION
pip install -r requirements.txt
