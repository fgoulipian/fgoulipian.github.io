# Breakout Strategy

Part of my Udacity **AI for Trading** Nanodegree (project passed on review).

## What it does
Implements a breakout signal from rolling highs and lows, filters out noisy signals, and runs a long-short backtest.

## Files
- `project_2_starter.ipynb` is the notebook with my solution and its saved outputs.
- Helper and test modules (`project_helper.py`, `project_tests.py`, `tests.py`) are the Udacity project scaffolding, kept so the notebook imports resolve.
- `requirements.txt` (where present) lists the package versions the course used.

## Data (not included)
Daily end-of-day prices (`eod-quotemedia.csv`, QuoteMedia via Udacity).

The datasets belong to Udacity and its data providers, so they are not in this repository. The notebook shows its outputs as saved, so you can read the results without running it. To rerun it, place your own copy of the data where the notebook's `read_csv` / `open` paths expect it.
