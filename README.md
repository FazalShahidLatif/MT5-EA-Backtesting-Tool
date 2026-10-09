# MT5 EA Backtesting Tool

Automated Expert Advisor backtesting and validation tool for MetaTrader 5.

## Features

- Run backtests on MT5 EAs with custom parameters
- Generate comprehensive performance reports
- Walk-forward analysis for robustness testing
- Monte Carlo simulation for risk assessment
- Multi-timeframe validation

## Key Metrics Tracked

| Metric | Description |
|---|---|
| Profit Factor | Gross profit / Gross loss |
| Drawdown | Maximum peak-to-trough decline |
| Expectancy | Average profit per trade |
| Win Rate | Percentage of winning trades |
| Sharpe Ratio | Risk-adjusted return |

## Usage

1. Copy your EA to the `Experts` folder
2. Configure backtest parameters in `config.ini`
3. Run `python backtest_runner.py`
4. Review generated reports in `reports/`

## Requirements

- MetaTrader 5
- Python 3.8+
- MetaTrader5 Python package

## Author

Fazal Shahid Latif — Trader since 2016 | EA Testing & Validation Specialist

---

[Upwork Profile](https://www.upwork.com/freelancers/~01291e05705df2c4e9) | [GitHub](https://github.com/FazalShahidLatif)
