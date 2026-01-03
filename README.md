
# Time Series Forecasting Benchmark

Benchmarking classical and machine learning models for time series forecasting, with a focus on reproducibility, rigorous evaluation, and comparative analysis.

---

## Objectives

- Compare classical statistical models and machine learning–based forecasting approaches  
- Apply robust and realistic validation strategies for time series data  
- Evaluate model performance using standardized and widely adopted metrics  

---

## Project Structure
```
time-series-forecasting-benchmark/
│
├── data/
│   ├── raw/                    # Original, immutable datasets
│   └── processed/              # Cleaned and transformed datasets
│
├── notebooks/                  # Exploratory analysis and experiments (Jupyter notebooks)
│
├── reports/
│   └── figures/                # Generated plots and visualizations
│
├── src/
│   ├── data/
│   │   └── load_data.py        # Data loading and preprocessing utilities
│   │
│   ├── features/
│   │   └── build_features.py  # Feature engineering for time series
│   │
│   ├── models/
│   │   └── train_model.py     # Model training scripts
│   │
│   ├── evaluation/
│   │   └── evaluate_model.py  # Model evaluation and metrics
│   │
│   └── utils/
│       └── config.py          # Configuration files and global settings
│
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation
└── .gitignore                  # Files and folders ignored by Git
````

## Validation Strategy

- Rolling and expanding window cross-validation  
- Clear separation of training, validation, and test sets  
- Prevention of data leakage in temporal evaluation  

---

## Evaluation Metrics

- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- Mean Absolute Percentage Error (MAPE)  

---

## Reproducibility

- Fixed random seeds  
- Explicit environment and dependency specification  
- Structured and modular code organization  

---
Notes

This repository is designed as a research-oriented benchmark framework.
The structure and evaluation protocol follow best practices for time series forecasting and are suitable for academic research, applied machine learning studies, and reproducible experimentation.
