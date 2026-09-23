# Campus Space Project

A reproducible data project summarizing observed seating utilization across synthetic campus study spaces.

## Data

The data used in this project represents synthetic teaching records. The tracked sample data is located at:
`data/sample/campus_spaces.csv`

For detailed variable descriptions, refer to the [Data Dictionary](docs/data_dictionary.md).

## Repository Structure

- `scripts/`: Source R code for processing and summarizing observations.
- `data/sample/`: Tracked sample data files.
- `docs/`: Project documentation and data dictionaries.
- `outputs/`: Scratch directory for generated outputs (ignored by version control).

## Requirements

- Tested with R via `Rscript`.
- Uses base R; no additional R packages are required.

## How to Run

Execute the analysis from the repository root:

```bash
Rscript scripts/summarize_spaces.R data/sample/campus_spaces.csv