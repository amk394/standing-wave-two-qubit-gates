# Standing-Wave Two-Qubit Gates

Code for generating figures from the paper “Efficient optical configurations for trapped-ion entangling gates” by A. M. Kolhatkar and K. K. Mehta, https://arxiv.org/abs/2509.05271.

## Overview

Laser configurations using a combination of optical standing waves and Gaussian beams (referred to as "running waves" in the paper) can be used to engineer state-dependent forces on trapped-ion qubits and realize high-fidelity two-qubit entangling gates while mitigating gate errors from spontaneous photon scattering. This repository provides:

- Code to calculate electric dipole matric elements and the resulting two-photon Rabi frequencies for two-qubit gates driven by Raman processes
- Numerical calculations of spontaneous scattering-induced gate errors following the analysis in the paper  
- Scripts for reproducing figures from the paper  

## Files

```
standing-wave-two-qubit-gates/
│
├── calculations.ipynb             # Main notebook for calculations and figure generation
├── atom_data.json                 # Atomic parameters used in modeling
├── experimental_parameters.json   # Relevant laser and experimental configuration parameters
├── LICENSE                        # MIT license
└── README.md                      # Project documentation
```

## Requirements

Typical dependencies include:

- Python ≥ 3.9
- NumPy
- SciPy
- Matplotlib
- Jupyter / JupyterLab

Install dependencies with:

```bash
pip install numpy scipy matplotlib jupyter
```

## Citation

If you use this repository, please cite: A. M. Kolhatkar and K. K. Mehta, "Efficient optical configurations for trapped-ion entangling gates", PRA (2026).

## License

This project is released under the MIT License. See LICENSE for details.

## Contact

For questions or collaborations, please contact Aditya Kolhatkar at amk394@cornell.edu.
