# Diffusion2D-Python-Package

## Project description

This code solves the diffusion equation in 2D over a square domain which is at a certain temperature and a circular disc at the center which is at a higher temperature. This code solves the diffusion equation using the Finite Difference Method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package

### Using pip3 to install from PyPI

```bash
pip3 install marquaml-diffusion2D
```

### Required dependencies

- Python version >= 3.6
- numpy
- matplotlib

## Running this package

```python3
from marquaml_diffusion2D import solve
solve()
```

or

```bash
diffusion2d-solve
```

## Citing
