# Ouro Quant Research

Systematic quantitative research across global macro, FX, and APAC equity markets.

Each strategy memo includes: hypothesis, signal construction with mathematical notation, backtested equity curve, regime analysis, and honest limitations.

---

## Strategy Index

| # | Strategy | Market | Status | Sharpe |
|---|----------|--------|--------|--------|
| 001 | [USD/KRW BOK Intervention Mean-Reversion](strategies/001-usdkrw-bok-intervention/memo.ipynb) | FX | In Testing | TBD |

---

## Structure

```
/strategies
  /001-[name]
    memo.ipynb    ← full research note: math, charts, backtest, stats
    README.md     ← one-paragraph summary
```

## Methodology

- All backtests use out-of-sample validation (in-sample: 2015–2022, OOS: 2023–present)
- Transaction costs included in all return calculations
- Regime analysis on every strategy
- Limitations section is mandatory

---

*Cooper Williams | Ouro Insights | [ouroinsights.substack.com](https://ouroinsights.substack.com)*
