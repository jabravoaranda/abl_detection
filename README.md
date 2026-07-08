# ABLH ceilometer workbench

Clean Jupyter workbench for estimating atmospheric boundary layer height from
ceilometer data using simple methods.

The main notebooks are:

- `ablh_batch_workbench.ipynb`: robust batch processing loop for one or more dates.
- `ablh_monthly_api_batch_workbench.ipynb`: one-month batch loop using raw ICENET files and Cloudnet API downloads.
- `ablh_single_date_workbench.ipynb`: direct execution for one date using the selected WCT parameters.
- `ablh_wct_sensitivity_study.ipynb`: WCT threshold/width sensitivity study for one date.

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
