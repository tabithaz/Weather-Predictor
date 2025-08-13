# Weather Prediction

Machine learning model that forecasts the **next day’s maximum temperature** using NOAA weather data (1970–2022). Built with **Python**, **Pandas**, and **Scikit-learn**, featuring extensive **feature engineering** and **rolling backtesting**.

## Key Points
- Predicts tomorrow’s `tmax` using past temperatures, precipitation, and seasonal trends.
- Handles missing data and removes anomalies.
- Creates rolling averages, percentage changes, and monthly/day-of-year averages.
- Uses **Ridge Regression** (`alpha=0.1`) to reduce overfitting.
- Backtesting shows **4.79°F MAE** after feature engineering.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib

## Run
```bash
git clone https://github.com/yourusername/jfk-temperature-prediction.git
cd jfk-temperature-prediction
pip install -r requirements.txt
jupyter notebook temperature_prediction.ipynb
