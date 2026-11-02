# FMCG Demand Planning and Forecasting

Capstone project for Data Ladder(Data Scientist Track). 

A time series analysis of three years of daily
FMCG sales (1.1M rows, 13 stores, 7 European countries, 102 SKUs) to understand
the drivers of demand and forecast it.

**Status:** in progress (Steps 1 and 2 complete)

## Repository structure

```
├── data/          Data instructions (the dataset itself is not stored here)
├── notebooks/     Jupyter notebooks
├── scripts/       Python scripts for preprocessing and training (added later)
├── .gitignore
└── README.md
```

## Getting started

### 1. Requirements
- Python 3 (Anaconda is recommended)
- Packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `jupyter`
  (`sqlite3` is included with Python)


### 2. Get the data
The dataset is about 212 MB, so it is not included in this repository.
See [`data/README.md`](data/README.md) for the source and the filename to use.

```
data/fmcg_sales_3years_1M_rows.csv
```

### 3. Run the notebooks
1. Start Jupyter notebook from inside the `notebooks/` folder. 
Running the notebook creates these files automatically. They are not tracked by Git:

| File | Created by | Purpose |
|---|---|---|
| `data/fmcg.db` | Step 1 | SQLite database used for the SQL queries |
| `data/processed/sales_clean.csv.gz` | Step 1 | Cleaned sales data with the promotion calendar merged in |
| `data/processed/sku_segments.csv` | Step 2 | ABC/XYZ class of each SKU |

## Project progress

| Step | Description | Status |
|---|---|---|
| 1 | Data preparation and SQL retrieval | Done |
| 2 | Exploratory data analysis and segmentation | Done |
| 3 | Statistical testing | In progress |
| 4 | Feature engineering | To do |
| 5 | Machine learning forecasting | To do |
| 6 | Explainability and ethics | To do |

## Technical summary
*To be added when the project is complete.*

## Tools used
- Jupyter noteboks
