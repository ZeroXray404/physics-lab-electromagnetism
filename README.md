# Physics Lab – Electromagnetism

Experimental investigation of magnetic force and magnetic flux density in current-carrying solenoids.

## Objective

Investigate how electric current, the number of coil turns and coil length affect the magnetic force between a solenoid and a permanent magnet.

## Technologies

- Python
- Pandas
- NumPy
- Plotnine
- Jupyter Notebook
- uv

## Methodology

The experimental measurements are processed using Python to calculate magnetic force and magnetic flux density. The results are visualized using scientific plots and evaluated through linear regression.

## Setup

Install the pinned Python version and locked project dependencies:

```
uv sync --locked
```

Open `analysis.ipynb` in VS Code and select the project's `.venv` under **Select Kernel → Python Environments**.

`.python-version` pins Python 3.13.15 because VS Code can save incomplete Python version metadata for a uv environment created with only `3.13` specified.
If VS Code still shows an incomplete version, move the existing `.venv` to an unused backup name, run `uv sync --locked` again, and reload the VS Code window before selecting the new `.venv`.

## Project structure

- `data/` – Raw experimental measurements.
- `figures/` – Generated scientific plots.
- `analysis.ipynb` – Calculations, data analysis and visualization.

## Purpose

This repository accompanies a laboratory report in Physics 2 and provides transparency and reproducibility of the scientific data analysis.
