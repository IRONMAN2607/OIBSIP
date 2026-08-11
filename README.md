# Oasis Infobyte - Data Science Internship

This repository contains my solutions for the Oasis Infobyte Data Science internship tasks. Each project is kept in its own notebook so that the data preparation, exploration, modelling, and evaluation can be followed in one place.

## Projects

| Task | Notebook | Focus |
| --- | --- | --- |
| 1 | Iris Flower Classification | Comparing classifiers for iris species prediction |
| 2 | Unemployment Analysis | Exploring unemployment trends in India |
| 3 | Car Price Prediction | Estimating resale prices from vehicle details |
| 4 | Email Spam Detection | Classifying SMS messages as spam or ham |
| 5 | Sales Prediction | Estimating sales from advertising spend |

## Repository layout

```text
notebooks/  Source notebooks, organised by task
data/       Local datasets used by a notebook (when available)
outputs/    Executed notebook copies kept as a record of results
```

## Running a notebook

Clone the repository, install the dependencies, then start Jupyter from the repository root:

```bash
pip install -r requirements.txt
jupyter notebook
```

Open a notebook from `notebooks/` and run the cells in order. All required datasets are included in `data/`, so the notebooks run without downloading files. The loaders also support their documented online fallbacks if a dataset is removed locally.

## Notes

- Models use a fixed random seed where a train/test split is involved, so results are reproducible.
- The results are intended as project work and exploratory analysis, not production predictions.
- Notebook loaders find `data/` whether Jupyter is started from the repository root or from the `notebooks/` directory.
