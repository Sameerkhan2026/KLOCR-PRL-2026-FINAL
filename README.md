# KLOCR-PRL-2026-FINAL

**Paper:** KLOCR Field Theory: ΛCDM Excluded at 21.1σ via Local Vacuum Permittivity  
**Author:** Sameer Khan  
**PRL ID:** es2026may02_575 - Submitted 02 May 2026  
**Contact:** xardarsameer555@gmail.com  

KLOCR with K0 = 0.917 resolves Hubble tension and JWST crisis.  
Reports **21.1σ preference over ΛCDM**: Δχ² = 444.97 using Planck 2018 TT+lowE.  
χ²_KLOCR = 7441.23 vs χ²_ΛCDM = 7886.2

## How to Reproduce in 3 Steps

1. Install CAMB: https://camb.info/
2. Run: `python camb KLOCR_CAMB.ini`
3. Run: `python chi2_calc.py` to verify Δχ² = 444.97

## Files in This Repository

- [KLOCR_Paper.pdf](KLOCR_Paper.pdf) - Full manuscript submitted to PRL
- [KLOCR_CAMB.ini](KLOCR_CAMB.ini) - Exact CAMB parameters: H0=73.0, w=-1.03, K0=0.917
- [chi2_calc.py](chi2_calc.py) - Python script that calculates Δχ² from CAMB output

## Status

Under review at Physical Review Letters. This repository was made public on submission date to ensure full reproducibility. Zenodo DOI will be added upon acceptance.
