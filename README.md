 Evaluation Quality 3D (EQ3D)


<p align="center">
    <img alt="Made with Python" src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?color=%23539fc9">
</p>

## Installation

### Clone the project:

#### SSH:
```bash
git clone git@github.com:RomainDaguerre/projet_court.git
```
OR
#### HTTPS:
```bash
git clone https://github.com/RomainDaguerre/projet_court
```

### Move to the new directory:
```bash
cd projet_court
```

### Install [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

### Create a Conda environment

```bash
conda env create -f DL_env.yml
```

### Activate the Conda environment

```bash
conda activate DL_env
```

### You can also update the conda environment with:

```bash
mamba env update -f binder/DL_env.yml
```

### To deactivate an conda active environment, use

```
conda deactivate
```

## Notebook

### MNIST:
```bash
jupyter notebook Projet_MNIST.ipynb
```

### Localization:
```bash
jupyter notebook Projet_localization.ipynb
```
