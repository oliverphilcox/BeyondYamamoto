# BeyondYamamoto
Simple implementation of the pairwise power spectrum and correlation function estimators of Philcox &amp; Slepian 2021. This computes the functions using either the midpoint or bisector line-of-sight definition for a chunk of the BOSS data-set or MultiDark-Patchy mocks.

There are two notebooks:
- ```Beyond Yamamoto Coefficients.ipynb```: Compute the coupling coefficients for the bisector and midpoint series expansions.
- ```Beyond Yamamoto Estimators.ipynb```: Run the pairwise estimators on data and plot the results.

### Dependencies:
- Python (2 or 3)
- Sympy (for spherical harmonic manipulations)
- nbodykit (for particle read-in)
- pyfftw (for Fourier transforms)
