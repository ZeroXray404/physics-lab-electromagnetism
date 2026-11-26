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

`.python-version` pins the full Python version because VS Code can report `3.13.x` for a uv environment created with a minor-only pin and save `3.13.-1` in the notebook metadata.
If your `.venv` was created with the old pin, rename it to `.venv.bak`, run `uv sync --locked` again, and reload the VS Code window before selecting the kernel.

## Project structure

- `data/` – Raw experimental measurements.
- `figures/` – Generated scientific plots.
- `analysis.ipynb` – Calculations, data analysis and visualization.

## Purpose

This repository accompanies a laboratory report in Physics 2 and provides transparency and reproducibility of the scientific data analysis.
