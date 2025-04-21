# Inverted Index with Phrase Query

This repository provides a simple Python implementation of an **inverted index with positional posting lists**, plus a function for running **exact phrase queries** over a small collection of documents.

## Features

- Build an inverted index mapping each token to:
  - A dictionary of document IDs → sorted list of positions where the token appears.
- Run exact phrase queries (e.g. `"data science"`) that return all document IDs containing the phrase.

## Contents

- `inverted_index.py`  
  - `build_inverted_index_with_positions(docs)`  
  - `phrase_query(index, phrase, docs)`

- `example_usage.ipynb` (optional)  
  A Jupyter notebook demonstrating how to build the index and run queries.

## Requirements

- Python 3.6+
- (Optional) Jupyter Notebook / JupyterLab for interactive demo

## Installation

1. **Clone this repository**  
   ```bash
   git clone https://github.com/<your‑username>/<your‑repo>.git
   cd <your‑repo>
