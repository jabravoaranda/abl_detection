# ABLH ceilometer workbench

This folder contains a clean Jupyter notebook for estimating atmospheric
boundary layer height from ceilometer data:

- `ablh_clean_workbench.ipynb`

The notebook uses raw data for the ABLH calculation and Cloudnet data as a
noise mask.

## Environment

Create and sync the environment with:

```powershell
uv sync
```

Then start Jupyter with:

```powershell
uv run jupyter lab
```

Inside Jupyter, open `ablh_clean_workbench.ipynb` and select the kernel from
this environment if needed.
