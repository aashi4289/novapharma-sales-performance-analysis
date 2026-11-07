# NovaPharma Sales Performance Analysis

A Python-based sales analysis project examining year-over-year performance, regional contribution, customer-tier mix, state-level changes and sales trends.

## Tools & technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express (imported in the notebook)

## Project overview
The analysis compares sales and unit performance for 2015 and 2016 across regions, states, customer tiers, months and business divisions.

## Business questions explored
- Which regions contributed to sales growth in 2016?
- How much does each customer tier contribute to revenue?
- Which states experienced a decline in sales?
- Are there monthly or quarterly sales patterns?
- Which divisions show changes in unit volumes, including within High-tier accounts?

## Key analysis components
- Data profiling, missing-value checks, duplicate checks and summary statistics
- Year-over-year sales growth calculations
- Region-, state- and customer-tier comparisons
- Monthly and quarterly trend analysis
- Division-level unit comparisons
- Visual reporting using bar charts, line charts, pie charts and a heatmap

## Python notebook
Open `notebooks/NovaPharma_Sales_Analysis.ipynb` in Jupyter Notebook or JupyterLab.

## Data file required
The source dataset is not included in this repository. Place the authorized dataset at `data/SalesData.csv`. The notebook uses this relative path. Do not upload confidential, personal or licensed data unless you have permission to share it.

## How to run
1. Clone or download this repository.
2. Install the required packages: `pandas`, `numpy`, `matplotlib`, `seaborn` and `plotly`.
3. Add `SalesData.csv` to the `data/` folder.
4. Open and run `notebooks/NovaPharma_Sales_Analysis.ipynb`.

## Repository structure
```text
novapharma-sales-performance-analysis/
├── notebooks/
│   └── NovaPharma_Sales_Analysis.ipynb
├── data/                  # Add source CSV locally; not tracked
├── .gitignore
└── README.md
```
