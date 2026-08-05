# USDCHF 1d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-14_288_rows-blue)](https://getdata.finance/datasets/usdchf) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdchf)

### -> [**Download the full USDCHF dataset on getdata.finance**](https://getdata.finance/datasets/usdchf)

**USDCHF 1d OHLCV forex historical data** — ultra high-quality 1d OHLCV for **US Dollar / Swiss Franc**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1d OHLCV** for **US Dollar / Swiss Franc** (Forex)
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **4 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdchf) · **14,288** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `USDCHF_1d.csv` (14,288 rows, `1971-01-04` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdchf)** — **14,288** `1m` rows (~1.18 MB), **4 timeframes** (1m · 15m · 12H · 1D), `1971-01-04` -> `2026-07-31`.

## Download sample

**[USDCHF_1d.csv](https://github.com/getdata-finance/usdchf-1d-ohlcv-forex-historical-data/blob/main/USDCHF_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdchf-1d-ohlcv-forex-historical-data/main/USDCHF_1d.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdchf-1d-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdchf-1d-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdchf-1d-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdchf](https://getdata.finance/datasets/usdchf)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdchf))** |
|---|--:|---|
| Instrument | US Dollar / Swiss Franc · Forex | US Dollar / Swiss Franc · Forex |
| Timeframes | `1d` (sample) | **4** — 1m · 15m · 12H · 1D |
| 1m rows | 14,288 | **14,288** |
| Size | 1.19 MB | ~1.18 MB |
| Period | `1971-01-04` -> `2026-07-31` | `1971-01-04` -> `2026-07-31` |
| File | `USDCHF_1d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdchf) |
| Coverage report | — | [USDCHF coverage](https://getdata.finance/coverage/usdchf) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdchf)**, each full asset archive is delivered as a ZIP with **4 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **15m** · **12H** · **1D**

GitHub = `1d` sample · [getdata.finance](https://getdata.finance/datasets/usdchf) = all **4** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCHF_1d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 1971-01-04T00:00:00+00:00 | 4.318 | 4.318 | 4.318 | 4.318 | 0 |
| 1971-01-05T00:00:00+00:00 | 4.318 | 4.318 | 4.318 | 4.318 | 0 |
| 1971-01-06T00:00:00+00:00 | 4.318 | 4.318 | 4.318 | 4.318 | 0 |
| 1971-01-07T00:00:00+00:00 | 4.318 | 4.318 | 4.318 | 4.318 | 0 |
| 1971-01-08T00:00:00+00:00 | 4.318 | 4.318 | 4.318 | 4.318 | 0 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27T00:00:00+00:00 | 0.83001 | 0.83405 | 0.82852 | 0.83309 | 144499 |
| 2026-07-28T00:00:00+00:00 | 0.83309 | 0.83517 | 0.83142 | 0.83329 | 112050 |
| 2026-07-29T00:00:00+00:00 | 0.83329 | 0.83535 | 0.82788 | 0.82788 | 204115 |
| 2026-07-30T00:00:00+00:00 | 0.82788 | 0.83212 | 0.81851 | 0.8196 | 253162 |
| 2026-07-31T00:00:00+00:00 | 0.8196 | 0.82302 | 0.81884 | 0.82302 | 94170 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDCHF_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCHF_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('USDCHF_1d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **USDCHF** archive on **[getdata.finance](https://getdata.finance/datasets/usdchf)** includes **4 OHLCV timeframes** (1m · 15m · 12H · 1D) — **14,288** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full USDCHF dataset on getdata.finance](https://getdata.finance/datasets/usdchf)**

---
*GetData · USDCHF 1d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdchf) · 2026-08-05 UTC*
