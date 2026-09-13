# Melbourne Suburb Analytics
 
Exploratory data analysis and inferential statistics on the Melbourne Housing Snapshot dataset.
 
## What it does
 
Cleans and investigates the Melbourne Housing Snapshot dataset, then answers eight statistical questions spanning hypothesis testing, correlation, simple and multiple linear regression, confidence intervals, and both binary and categorical prediction.  
The project is uses two notebooks: [`01_cleaning.ipynb`](https://github.com/cousc0us/melbourne-suburb-analytics/blob/main/notebooks/01_cleaning.ipynb) handles data cleaning and manages dtype/outlier values, where [`02_analysis.ipynb`](https://github.com/cousc0us/melbourne-suburb-analytics/blob/main/notebooks/02_analysis.ipynb) runs the core analysis.
 
## Why I built it
 
This is my first personal project, where I thought of combining the mathematical statistic skills (hypothesis testing, regression, confidence intervals) I already know with code for analysis.  
Also wanted to learn the basics of cleaning data on a raw dataset.
 
## Tech stack
 
Python, pandas, numpy, matplotlib, scipy.stats, statsmodels, Jupyter
 
## Key findings
 
- **Q1 — Price by property type:** _pending_
- **Q2 — Correlation between price and its likely predictors:** _pending_
- **Q3 — Distance-only regression baseline:** _pending_
- **Q4 — Multiple regression (Rooms, Bathroom, BuildingArea):** _pending_
- **Q5 — Confidence interval on a sample mean:** _pending_
- **Q6 — Price by sale method (ANOVA):** _pending_
- **Q7 — Above/below median price prediction:** _pending_
- **Q8 — Price differences by region:** _pending_
 
## What I'd do differently
 
_pending_
 
## Project file structure
 
_pending_
 
## How to run the code (bash)
 
```bash
git clone https://github.com/cousc0us/melbourne-suburb-analytics.git
cd melbourne-suburb-analytics
mkdir -p data/raw data/processed
pip install -r requirements.txt
jupyter notebook
```
 
Run `01_cleaning.ipynb` first so it cleans the raw dataset > imports into `data/processed/melb_data_cleansed.csv`  
Run `02_analysis.ipynb` next, which loads the analysis file.
 
Dataset: [Melbourne Housing Snapshot on Kaggle](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot).
Download and place the raw CSV in `data/raw/` before running.
