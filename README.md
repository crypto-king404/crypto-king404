# Sohan Hajra

**Quantitative research · Systematic trading · Market microstructure**

Mathematics & Computer Science graduate from the University of Illinois Urbana-Champaign (GPA: 3.76/4.00). I build research and trading systems that make assumptions, transaction costs, out-of-sample behavior, and failure modes inspectable.

Open to new-grad quantitative research, junior quantitative strategy, and systematic-trading roles in the United States and the UAE. UAE Golden Visa holder.

## Current research

### Systematic Trading Research Platform

An independent Python research platform for testing equity strategies with explicit data validation, transaction costs, walk-forward evaluation, and attribution.

- Built an OHLCV pipeline with DuckDB storage, parameter sweeps, and rolling 12-month training / 3-month out-of-sample evaluation.
- Evaluated a SPY long/flat trend baseline across 15 OOS folds at 5 bps transaction costs.
- Added trade-, regime-, portfolio-, and flat-period attribution to explain return drivers and benchmark shortfalls.
- Corrected warm-up and fold-accounting errors by isolating indicator history from OOS scoring and recomputing positions, costs, trades, and compounded equity after each test boundary.

| OOS trades | CAGR | Sharpe | Maximum drawdown | Market exposure |
|---:|---:|---:|---:|---:|
| 22 | 9.18% | 0.82 | -11.79% | 75.77% |

> Research baseline only—not live, audited, or investment performance. The public release will follow tests, documentation, a methodology and limitations memo, and a one-command reproduction workflow.

## Selected work

**Venue and USO/WTI ETF-Futures Arbitrage — C++ team project**  
Co-developed and backtested venue- and ETF-futures-arbitrage strategies using market-by-order data from NASDAQ, IEX, and CME. Tested timestamp normalization, quote-persistence filters, smart routing, and inventory-risk controls under execution constraints.

**Portfolio Reconstruction & Performance Attribution Engine — Python**  
Reconstructed daily NAV from brokerage ledgers, implemented time-weighted returns to separate investment performance from cash flows, and used rolling QQQ correlation to diagnose concentrated technology beta.

**Published research — NLP**  
Co-authored [“An N-Gram Framework for Sentiment and Emotion-Aware Word Association Games”](https://doi.org/10.1145/3774399.3774407), *ACM SIGAI AI Matters* 11(1), 49–58 (2025). The study combines n-gram co-occurrence and GloVe embeddings with VADER sentiment and SenticNet emotion signals.

## Experience

- **Morgan Stanley — BI & Data Analytics Intern:** automated fund-performance reporting and built data-quality tooling for Equities Data Operations.
- **The D. E. Shaw Group — Strategy & Business Development Intern:** built a quantitative market-ranking model and trading-venue intelligence for APAC expansion research.

## Technical focus

`Python` `C++` `SQL` `Pandas` `NumPy` `scikit-learn` `PyTorch` `DuckDB` `PostgreSQL` `Snowflake` `Docker` `Linux/Bash` `Git`

## Research principles

- Define the hypothesis and benchmark before tuning.
- Keep training history separate from out-of-sample scoring.
- Model costs, exposure, turnover, and implementation constraints.
- Report errors, limitations, and underperformance—not only headline metrics.

## Contact

[LinkedIn](https://www.linkedin.com/in/sohan-hajra/) · [Email](mailto:shajra2@illinois.edu)
