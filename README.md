This repository contains the two mandatory exercises:
Run `claims-forecasting/01_data_preparation.ipynb` through `04_error_analysis.ipynb` in numerical order.
Notebook `01` downloads the source data and creates the git-ignored local `data/` files required by later notebooks.

```text
business-assignment/
  business_assignment.ipynb
claims-forecasting/
  01_data_preparation.ipynb
  02_exploration.ipynb
  03_modelling.ipynb
  04_error_analysis.ipynb
```

## Running the notebooks

Use Python 3.11 or 3.12:

```bash
python -m venv .venv
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm pyarrow jupyter
jupyter notebook
```
