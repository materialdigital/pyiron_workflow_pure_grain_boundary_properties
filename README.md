# Pure grain boundary properties (pyiron_workflow)
This repository demonstrates computing pure grain boundary properties using the `pyiron_workflow` framework. The workflow is engine-agnostic and is demonstrated here with LAMMPS.

You can fork this repository and populate it with your own data.

## Installation
Create and activate the conda environment from the provided `environment.yml`:

```bash
# Using mamba (recommended)
mamba env create -f environment.yml -n pyiron-workflow-grain-boundary-properties
conda activate pyiron-workflow-grain-boundary-properties

# Or using conda
conda env create -f environment.yml -n pyiron-workflow-grain-boundary-properties
conda activate pyiron-workflow-grain-boundary-properties

# To update an existing environment after changes to environment.yml
mamba env update -f environment.yml -n pyiron-workflow-grain-boundary-properties
# or
conda env update -f environment.yml -n pyiron-workflow-grain-boundary-properties
```

## Run the workflow
Open and execute the notebook `pure_grain_boundary_study.ipynb` in this directory:

```bash
jupyter lab
# or
jupyter notebook
```

Then open `pure_grain_boundary_study.ipynb` and run all cells.