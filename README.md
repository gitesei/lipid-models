[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/gitesei/lipid-models/master)

# lipid-models
Coarse-grained lipid models for Monte Carlo simulations

![](https://github.com/gitesei/lipid-models/blob/master/bilayer.png =100x20)

### Layout

- `3bead.ipynb` Jupyter Notebook to launch Monte Carlo simulations of a highly coarse-grained lipid model using [Faunus](http://mlund.github.io/faunus/). This notebook guides you through a protocol to simulate planar lipid bilayers of the [3-bead Cooke model](https://aip.scitation.org/doi/10.1063/1.2135785) and to calculate thermodynamic properties such as the transition temperature and the thermal expansivity.
- `3bead/` Faunus simulation data for the 3-bead model

### Usage

To open the Notebooks, install python via [Miniconda](https://conda.io/miniconda.html) and make sure all required packages are loaded
by issuing the following terminal commands

```bash
    conda env create -f environment.yml
    source activate lipid-models
    jupyter-notebook
```
