# GOOG 1h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-21_817_rows-blue)](https://getdata.finance/datasets/goog) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/goog)

### -> [**Download the full GOOG dataset on getdata.finance**](https://getdata.finance/datasets/goog)

**GOOG 1h OHLCV stocks historical data** — ultra high-quality 1h OHLCV for **Alphabet**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1h OHLCV** for **Alphabet** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/goog) · **21,817** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `GOOG_1h.csv` (889 rows, `2026-03-26` -> `2026-09-25`, 54.95 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/goog)** — **21,817** `1h` rows (full `1m`: 634,121), **11 timeframes**, `2011-05-09` -> `2026-09-25`.

## Download sample

**[GOOG_1h.csv](https://github.com/getdata-finance/goog-1h-ohlcv-stocks-historical-data/blob/main/GOOG_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/goog-1h-ohlcv-stocks-historical-data/main/GOOG_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/goog-1h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/goog-1h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/goog-1h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/goog](https://getdata.finance/datasets/goog)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/goog))** |
|---|--:|---|
| Instrument | Alphabet · US stocks | Alphabet · US stocks |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 889 | **21,817** |
| Size | 54.95 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/goog) |
| Period | `2026-03-26` -> `2026-09-25` | `2011-05-09` -> `2026-09-25` |
| File | `GOOG_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/goog) |
| Coverage report | — | [GOOG coverage](https://getdata.finance/coverage/goog) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/goog)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/goog) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GOOG_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T13:00:00+00:00 | 298.59 | 298.59 | 291.97 | 294.31 | 12439 |
| 2026-03-26T14:00:00+00:00 | 294.31 | 295.55 | 293.63 | 294.17 | 20694 |
| 2026-03-26T15:00:00+00:00 | 294.17 | 294.36 | 292.65 | 292.92 | 14503 |
| 2026-03-26T16:00:00+00:00 | 292.92 | 293.2 | 291.63 | 292.26 | 13231 |
| 2026-03-26T17:00:00+00:00 | 292.26 | 292.52 | 290.4 | 290.52 | 13015 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T15:00:00+00:00 | 339.73 | 341.46 | 339.71 | 341.17 | 7657 |
| 2026-09-25T16:00:00+00:00 | 341.17 | 342.17 | 339.99 | 340.24 | 6655 |
| 2026-09-25T17:00:00+00:00 | 340.24 | 341.3 | 340.12 | 340.81 | 4729 |
| 2026-09-25T18:00:00+00:00 | 340.81 | 341.68 | 340.25 | 341.02 | 5408 |
| 2026-09-25T19:00:00+00:00 | 341.02 | 341.53 | 340.28 | 341.04 | 7453 |

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

df = pd.read_csv('GOOG_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GOOG_1h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('GOOG_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **GOOG** archive on **[getdata.finance](https://getdata.finance/datasets/goog)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **21,817** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full GOOG dataset on getdata.finance](https://getdata.finance/datasets/goog)**

---
*GetData · GOOG 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/goog)*
