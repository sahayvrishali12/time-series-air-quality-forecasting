
# 🌀 Time Series Air Quality Forecasting

A time series forecasting project to predict hourly air pollutant concentrations for the next 48 hours using statistical and machine learning models.

## 📊 Project Objective

To forecast the concentration of air pollutants using a dataset of 9358 hourly records. This project involves:

- Data preprocessing
- Feature engineering
- Time series modeling (ARIMA, Prophet, etc.)
- Residual and error analysis
- Model comparison using RMSE

---

## 🧰 Tech Stack & Tools

- **Python** (Pandas, NumPy, scikit-learn)
- **Time Series Models**: ARIMA, Facebook Prophet, etc.
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Jupyter Notebook** for development
- **Report**: Comparative analysis in PDF format

---

## 📁 Project Structure

```
time-series-air-quality-forecasting/
├── data/
│   └── air_quality.csv                  # Input dataset
├── notebooks/
│   └── EDA_and_modeling.ipynb           # Jupyter notebook with all code
├── models/
│   └── prophet_model.pkl (optional)     # Saved models (if used)
├── results/
│   ├── rmse_comparison.png              # Model comparison visuals
│   └── forecast_plot.png                # Forecast output
├── report/
│   └── air_quality_forecasting_report.pdf
├── requirements.txt                     # Python dependencies
└── README.md
```

---

## 📈 Models Used

- **ARIMA**
- **Facebook Prophet**
- (Optional: LSTM or XGBoost if included)

Each model was trained and validated using the same train-test split. Performance was evaluated using RMSE.

---

## 📊 Evaluation Metrics

| Model     | RMSE (Validation Set) |
|-----------|------------------------|
| ARIMA     |  *e.g. 35.2 µg/m³*     |
| Prophet   |  *e.g. 28.7 µg/m³*     |

*(Actual values should be filled in based on your results)*

---

## 🔍 Key Insights

- Feature engineering (lags, rolling means) significantly improved accuracy.
- Prophet outperformed ARIMA due to its handling of seasonality.
- Residual analysis showed white-noise-like behavior, indicating good model fit.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/time-series-air-quality-forecasting.git
cd time-series-air-quality-forecasting
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
Open `notebooks/EDA_and_modeling.ipynb` and run all cells to see the complete analysis and forecast.

---

## 📄 License

MIT License

---

## 👤 Author

**Vrishali**  
Advanced Engineering Mathematics & Data Science Enthusiast  
📧 *[Add your email or GitHub profile link]*
