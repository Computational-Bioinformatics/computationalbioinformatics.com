---
title: "Tools and Environments"
---

# Tools and Environments

This page describes a recommended setup for course work and a checklist for getting started.

## Recommended software

- **Miniconda** or **Mamba** for package management.
  - https://docs.conda.io/en/latest/miniconda.html
  - https://mamba.readthedocs.io/en/latest/installation.html
- **Python 3.11+**
  - Core language for notebooks and scripting.
- **Jupyter** (Lab or Notebook)
  - https://jupyter.org/
- **Git + GitHub**
  - https://git-scm.com/
  - https://github.com/
- **BLAST**
  - https://blast.ncbi.nlm.nih.gov/Blast.cgi
- **Biopython**
  - https://biopython.org/

## Suggested environment checklist

- Install Python and a package manager.
- Create a new environment for this course.
- Install core libraries: `biopython`, `pandas`, `numpy`, `matplotlib`.
- Open a notebook and run a short test script.

## Example conda workflow

```bash
conda create -n bioinfo python=3.11
conda activate bioinfo
conda install biopython pandas numpy matplotlib
pip install jupyterlab
```

## Reproducibility tips

- Keep environment files (e.g., `environment.yml`).
- Record software versions in reports.
- Use clear file naming and folder structure.

## Suggested class activity

- Set up a new environment and run a short sequence parsing script.
