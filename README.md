# AMD 12h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_370_rows-blue)](https://getdata.finance/datasets/amd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/amd)

### -> [**Download the full AMD dataset on getdata.finance**](https://getdata.finance/datasets/amd)

**AMD 12h OHLCV stocks historical data** — ultra high-quality 12h OHLCV for **Advanced Micro Devices**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **Advanced Micro Devices** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/amd) · **1,370** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `AMD_12h.csv` (127 rows, `2026-03-26` -> `2026-09-25`, 11.72 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/amd)** — **1,370** `12h` rows (full `1m`: 525,821), **11 timeframes**, `2021-04-13` -> `2026-09-25`.

## Download sample

**[AMD_12h.csv](https://github.com/getdata-finance/amd-12h-ohlcv-stocks-historical-data/blob/main/AMD_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/amd-12h-ohlcv-stocks-historical-data/main/AMD_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/amd-12h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/amd-12h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/amd-12h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/amd](https://getdata.finance/datasets/amd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/amd))** |
|---|--:|---|
| Instrument | Advanced Micro Devices · US stocks | Advanced Micro Devices · US stocks |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 127 | **1,370** |
| Size | 11.72 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/amd) |
| Period | `2026-03-26` -> `2026-09-25` | `2021-04-13` -> `2026-09-25` |
| File | `AMD_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/amd) |
| Coverage report | — | [AMD coverage](https://getdata.finance/coverage/amd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/amd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/amd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AMD_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T12:00:00+00:00 | 220 | 220.46 | 203.11 | 203.57 | 69940 |
| 2026-03-27T12:00:00+00:00 | 203.57 | 203.57 | 197.36 | 201.61 | 63754.4702 |
| 2026-03-30T12:00:00+00:00 | 201.61 | 208.02 | 192.56 | 195.82 | 127991 |
| 2026-03-31T12:00:00+00:00 | 195.82 | 203.68 | 195.82 | 202.75 | 138442 |
| 2026-04-01T12:00:00+00:00 | 202.75 | 213.51 | 202.75 | 209.96 | 102968 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-21T12:00:00+00:00 | 559.59 | 616.43 | 559.59 | 615.08 | 60585 |
| 2026-09-22T12:00:00+00:00 | 615.08 | 624.31 | 605.85 | 623.66 | 63368 |
| 2026-09-23T12:00:00+00:00 | 623.66 | 623.83 | 607.83 | 614.57 | 40957 |
| 2026-09-24T12:00:00+00:00 | 614.57 | 630.51 | 599.09 | 628.76 | 56583 |
| 2026-09-25T12:00:00+00:00 | 628.76 | 638.62 | 625.32 | 630.33 | 37087 |

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

df = pd.read_csv('AMD_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AMD_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AMD_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **AMD** archive on **[getdata.finance](https://getdata.finance/datasets/amd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,370** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full AMD dataset on getdata.finance](https://getdata.finance/datasets/amd)**

---
*GetData · AMD 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/amd)*
