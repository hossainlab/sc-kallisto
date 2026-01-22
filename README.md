# sc-kallisto
A wrapper for the kallisto | bustools workflow for single-cell RNA-seq pre-processing

## Clone the repository

```bash
git clone https://github.com/hossainlab/sc-kallisto.git
cd sc-kallisto
```

## Open with Jupyter Lab 
Make sure you have Jupyter Lab installed in your conda environment. Then, run:

```bash
jupyter lab
```

## Folder Structure
- `notebooks/`: Contains the main scripts for running the kallisto | bustools workflow.
- `raw_data/`: Example datasets for testing the workflow.nce analysis.
- `results/`: Directory to store output results from the single-cell RNA-seq experiments.
- `environment.yml`: Conda environment file with all necessary dependencies.nce data processing.    
s
## Installation
Use `enronment.yml` to create a conda environment with all dependencies:

```bash
conda env create -f environment.yml
conda activate sc-kallisto
```

## Acknowledgements
This repository is inspired by and adapted from the [kb-python](https://github.com/pachterlab/kb_python) package.

We thank the developers of kallisto and bustools for their excellent tools for single-cell RNA-se
