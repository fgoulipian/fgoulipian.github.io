# NLP on Financial Statements

## What it does
Parses SEC 10-K filings, scores them with Loughran-McDonald sentiment word lists and TF-IDF similarity, and tests the resulting signals as alpha factors.

## Files
- `project_5_starter.ipynb` is the notebook with my solution and its saved outputs.
- Helper and test modules (`project_helper.py`, `project_tests.py`, `tests.py`) are the Udacity project scaffolding, kept so the notebook imports resolve.
- `requirements.txt` (where present) lists the package versions the course used.

## Data (not included)
SEC filings text, `yr-quotemedia.csv` prices and the Loughran-McDonald word lists (all via Udacity).

The datasets belong to Udacity and its data providers, so they are not in this repository. The notebook shows its outputs as saved, so you can read the results without running it. To rerun it, place your own copy of the data where the notebook's `read_csv` / `open` paths expect it.
