This repository contains the two mandatory exercises:

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

Run the notebooks in numerical order using Python 3.11 or 3.12:

```bash
python -m venv .venv
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm pyarrow jupyter
jupyter notebook
```

After the claims forecasting exercise has been completed, the results and the final modelling summary will be included.