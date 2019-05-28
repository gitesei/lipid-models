# lipid-models
Coarse-grained lipid models for Monte Carlo simulations

### Layout

- `3bead.ipynb` Jupyter Notebook to launch Monte Carlo simulations of the [3-bead Cooke model](https://aip.scitation.org/doi/10.1063/1.2135785) using [Faunus](http://mlund.github.io/faunus/)
- `3bead/` Faunus simulation data for the 3-bead model

### Usage

To open the Notebooks, install python via [Miniconda](https://conda.io/miniconda.html) and make sure all required packages are loaded
by issuing the following terminal commands

```bash
    conda env create -f environment.yml
    source activate lipid-models
    jupyter-notebook
```
