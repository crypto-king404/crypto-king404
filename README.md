# Sohan Hajra

**Quantitative research · Research engineering · Market microstructure**

Mathematics & Computer Science graduate from the University of Illinois Urbana-Champaign (GPA: 3.76/4.00). I build research tools that make assumptions, transaction costs, out-of-sample behavior, and failure modes inspectable.

Open to new-graduate quantitative research, quantitative development, research engineering, and systematic-trading roles in the United States and the UAE. UAE Golden Visa holder.

## Current research

### Systematic Trading Research Platform

An independent Python platform for testing equity strategies with explicit data validation, transaction costs, walk-forward evaluation, and attribution.

- Built an OHLCV pipeline with DuckDB storage, parameter sweeps, and rolling 12-month training / 3-month out-of-sample evaluation.
- Evaluated a SPY long/flat trend baseline across 15 out-of-sample folds at 5 bps transaction costs.
- Added trade, regime, portfolio, and flat-period attribution to explain return drivers and benchmark shortfalls.
- Corrected warm-up and fold-accounting errors by isolating indicator history from out-of-sample scoring and recomputing positions, costs, trades, and compounded equity after each test boundary.

| OOS trades | CAGR | Sharpe | Maximum drawdown | Market exposure |
|---:|---:|---:|---:|---:|
| 22 | 9.18% | 0.82 | -11.79% | 75.77% |

> Research baseline only. These are not live, audited, or client investment results. The strategy underperformed SPY buy-and-hold on return and Sharpe during the evaluated period.

## Selected work

**Venue and USO/WTI ETF-Futures Arbitrage - C++ team project**  
Co-developed and backtested venue- and ETF-futures-arbitrage strategies using market-by-order data from NASDAQ, IEX, and CME. Tested timestamp normalization, quote-persistence filters, smart routing, and inventory-risk controls under execution constraints.

**Portfolio Reconstruction & Performance Attribution Engine - Python**  
Reconstructed daily NAV from brokerage ledgers, implemented time-weighted returns to separate investment performance from cash flows, and used rolling QQQ correlation to diagnose concentrated technology beta.

**Published NLP research**  
Co-authored [“An N-Gram Framework for Sentiment and Emotion-Aware Word Association Games”](https://doi.org/10.1145/3774399.3774407), *ACM SIGAI AI Matters* 11(1), 49-58 (2025).

## Research and engineering experience

- **Spade Labs - Data Engineering Intern:** built a Dockerized market-research data pipeline and a PostgreSQL/pgvector ingestion workflow for embedding data.
- **Penn State University - Undergraduate Student Researcher:** helped develop and evaluate sentiment- and emotion-aware word-association models that led to the ACM SIGAI publication.

## Technical focus

`Python` `C++` `SQL` `Pandas` `NumPy` `scikit-learn` `PyTorch` `DuckDB` `PostgreSQL` `Docker` `AWS` `Linux/Bash` `Git`

## Research principles

- Define the hypothesis and benchmark before tuning.
- Keep training history separate from out-of-sample scoring.
- Model costs, exposure, turnover, and implementation constraints.
- Report errors, limitations, and underperformance, not only headline metrics.

## Contact

[LinkedIn](https://www.linkedin.com/in/sohan-hajra/) · [Email](mailto:shajra2@illinois.edu)
