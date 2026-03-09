# Retrieval Architecture Stress Test

Minimal reproducible experiment illustrating basis-conditioned
atmospheric retrieval in exoplanet spectroscopy.

This code reproduces the synthetic experiment presented in:

**Atmospheric Retrieval and Architectural Closure in Exoplanet Spectroscopy**
Danilo Tavella

## Description

The experiment generates a synthetic spectrum composed of H₂O and CH₄ absorption
features and performs two retrieval fits:

Retrieval A: H₂O + NH₃ (restricted basis)

Retrieval B: H₂O + CH₄ (correct basis)

The test illustrates how spectral structure can be redistributed among
available molecular components when the correct absorber is not included
in the retrieval architecture.

## Files

retrieval_basis_test.ipynb  
Notebook generating the synthetic spectrum and retrieval fits.

## Requirements

Python 3  
numpy  
matplotlib  
scipy
