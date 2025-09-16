# Air Quality Statistical Analysis — ISYE 3030 Final Project

## Elevator pitch
Data-driven study analyzing air quality across U.S. Core-Based Statistical Areas (CBSAs). I cleaned and consolidated multiple sources, performed exploratory data analysis, built regression models to test associations between air quality and socio-demographic indicators, and produced visualizations (including choropleths and scatter plots) to communicate findings.

## Tools & skills demonstrated
- Python: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, openpyxl
- Data cleaning & ETL: merging, missing-value handling, feature engineering, Excel export
- Statistical analysis: descriptive statistics, regression modeling, interpretation of coefficients
- Visualization: choropleth maps, distribution plots, scatterplots for insight communication
- Reproducible research: Jupyter Notebooks, well-structured data artifacts

## Key outcomes (recruiter summary)
- Produced a cleaned, analysis-ready dataset and a regression-ready subset.
- Generated clear visual evidence of air quality distribution and relationships with population and other indicators.
- Delivered a final report (PDF) and notebooks that document methods and results.

## Repo structure
- `ISYE3030FinalProject.pdf` — Final written report with methodology, results, and conclusions.
- `data/` — Raw and cleaned CSV/XLSX datasets used for analysis, including:
  - `cleaned_AQI.csv` / `.xlsx` — Cleaned Air Quality Index data
  - `FinalDataset.csv` / `.xlsx` — Consolidated dataset used for final analysis
  - `Regression_Dataset.csv` / `.xlsx` — Regression-ready file
- `figures/` — Visual outputs used in the report (examples: `AQI_Choropleth.png`, `Population_ScatterPlot.png`).
- `notebooks/` — Jupyter notebooks for cleaning and analysis
  - `Datasets Cleaning.ipynb` — data cleaning steps and transformation logic
  - `UpdatedDataset.ipynb` — dataset updates and exports
  - `Statistical_Analysis.ipynb` — EDA, modeling, and result interpretation

## How to run (quick steps)
1. Create and activate a Python virtual environment (macOS/zsh):

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install common dependencies (minimal set used in notebooks):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels openpyxl jupyterlab
```

3. Open and run the notebooks in `notebooks/` with JupyterLab or Jupyter Notebook. Start with `Datasets Cleaning.ipynb`, then `UpdatedDataset.ipynb`, and finally `Statistical_Analysis.ipynb`.

4. Figures are saved in `figures/`. Processed datasets are in `data/` (CSV/XLSX).

## How to read this for recruiting conversations
- Quick evidence of technical ability: point reviewers to `notebooks/Statistical_Analysis.ipynb` and `Regression_Dataset.csv` for modeling pipeline and inputs.
- Communication and impact: `ISYE3030FinalProject.pdf` contains an executive summary, methodology, and key findings suitable for non-technical stakeholders.
- Reproducibility: data cleaning is in `Datasets Cleaning.ipynb` and outputs are stored in `data/` for review.

## Suggested interview talking points
- Problem framing: why CBSAs and AQI matter for public health and policy.
- Data challenges: merging different sources, handling missingness, and ensuring regression assumptions.
- Modeling choices and interpretation: which features were predictive, how effect sizes map to practical impacts.