# Zeeman Splitting and Stellar Magnetic Fields

Exploratory Python/Jupyter simulations of Zeeman splitting and its signatures in stellar spectral lines, motivated by the study of magnetic fields in HD 101065 (Przybylski’s star).

## Notebook

[`Zeeman_Splitting_Simulations.ipynb`](Zeeman_Splitting_Simulations.ipynb) contains examples of:

- Wavelength splitting as a function of magnetic field and wavelength
- Allowed Zeeman transitions and relative component strengths using Wigner 3-j symbols
- Zeeman patterns for illustrative atomic transitions and Landé factors
- Synthetic absorption-line profiles with and without magnetic fields
- Effective Landé factor calculations
- Artificial noisy observations and a magnetic-field fitting example
- Interactive plotting with sliders
- Instrumental resolution and broadening

## Getting started

Install the packages in `requirements.txt`, then open the notebook in JupyterLab or Jupyter Notebook. Run cells in order. The interactive examples may require a compatible Jupyter widget backend.

```bash
pip install -r requirements.txt
jupyter lab
```

## Scientific context

For the illustrative splitting relation used in the notebook, with wavelength in Å and magnetic field in gauss:

Δλ = 4.67 × 10⁻¹³ λ² B

Actual component shifts depend on the magnetic quantum numbers and Landé factors of the lower and upper levels. The examples are educational simulations, not a calibrated determination of the magnetic field of HD 101065 from observational data.

## Notes

The original notebook cells and saved outputs are preserved. The notebook has not been fully rerun or independently validated as part of this packaging. Some cells are independent demonstrations and may reuse variable/function names; run with care when comparing examples.
