# ABLH ceilometer workbench

Clean Jupyter workbench for estimating atmospheric boundary layer height from
ceilometer data using simple methods.

The main notebook is:

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

Inside Jupyter, open `ablh_clean_workbench.ipynb` and select the
`Python (ablh-ceilometer-workbench)` kernel if needed.
