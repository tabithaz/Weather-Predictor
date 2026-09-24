# Weather Prediction

A notebook that forecasts the next day's maximum temperature from historical weather observations using pandas and scikit-learn Ridge regression. It includes feature engineering and rolling backtesting.

## Run

```bash
git clone https://github.com/tabithaz/Weather-Predictor.git
cd Weather-Predictor
python -m pip install pandas scikit-learn jupyter
jupyter notebook predict.ipynb
```

`weather.csv` is included. Open the notebook and run its cells in order to reproduce its metrics; backtesting estimates depend on the data and feature selection in the notebook.
