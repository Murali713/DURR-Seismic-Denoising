# DURR: Deep Unrolling Rank Reduction for Seismic Denoising

##  Overview

This repository presents **DURR (Deep Unrolling Rank Reduction)**, a physics-guided deep learning framework for seismic data denoising. The method integrates model-based low-rank approximation with data-driven learning through deep unrolling.

## Key Contributions

* Physics-guided deep unrolling framework
* Adaptive singular value learning via autoencoder
* Eliminates manual rank selection
* Preserves structural continuity in seismic data

##  Method Summary

The approach is based on:

* Frequency-domain Hankel matrix modeling
* Low-rank approximation using nuclear norm relaxation
* Proximal gradient unrolling into trainable stages
* Learned singular value shrinkage

##  Repository Structure

* `notebooks/` → Pseudocode and explanation
* `src/` → Core implementation
* `requirements.txt` → Dependencies

##  Installation

```bash
pip install -r requirements.txt
```

## Usage

Run the executable:

```bash
python src/DURR_Executable.py
```

Or open notebook:

```bash
jupyter notebook notebooks/DURR_Pseudocode.ipynb
```

##  Applications

* Seismic denoising
* Earthquake signal enhancement
* Exploration geophysics

##  License

MIT License

