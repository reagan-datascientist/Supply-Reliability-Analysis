# Supply-Reliability-Analysis
A toy model evaluating supply chain reliability and hedge effectiveness using sample data (2010–2023). Built in a Jupyter Notebook with Pandas, SciPy, and Statsmodels, it calculates baseline reliability ($\hat{\rho}$), simulates variance reduction ($\hat{\eta}^2$), and runs simple optimization routines to compare hedged vs. unhedged scenarios.


# Supply Reliability Analysis & Numerical Implementation

This repository contains the complete numerical implementation and empirical analysis framework for evaluating supply chain reliability, measuring hedging effectiveness, and optimizing operational quantities based on historical data (2010–2023).

The core analysis is built inside a Python Jupyter Notebook that integrates statistical modeling with optimization algorithms to compare hedged versus unhedged supply scenarios.

## 📊 Key Features & Analysis

- **Historical Data Processing:** Ingests and cleans 14 years of supply and export data (2010–2023).
- **Supply Reliability Framework:** Formulates and calculates the Base Supply Reliability ($\hat{\rho}$) indicator.
- **Risk Mitigation & Hedging:** Estimates the Hedge Effectiveness ($\hat{\eta}^2$) to determine variance reduction under risk management.
- **Optimization Engine:** Uses non-linear optimization (`scipy.optimize`) to determine optimal supply quantities and tracks how they scale alongside reliability metrics.
- **Value-at-Risk Improvement:** Compares the economic value of hedged ($v_{\text{hedged}}$) vs. unhedged ($v_{\text{unhedged}}$) strategies to output an Average Value Improvement percentage.

## 🛠️ Technologies & Libraries Used

The implementation relies on the standard Python scientific computing ecosystem:
* **Pandas & NumPy** – Data structuring, array manipulation, and mathematical formulations.
* **SciPy** – Optimization subroutines (`minimize`, `minimize_scalar`) and statistical distributions.
* **Statsmodels** – Linear and advanced regression modeling.
* **Matplotlib** – Data visualization using clean, modern plot configurations (`seaborn-v0_8-darkgrid`).

## 🚀 Getting Started

### Prerequisites

To run this notebook locally, ensure you have Python 3.8+ installed along with the required libraries. You can install everything via `pip`:

```bash
pip install pandas numpy matplotlib scipy statsmodels notebook
