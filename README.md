# Yield curve dynamics and portfolio risk

Start with Advanced_Findings.pdf, then run Advanced_Yield_Curve.ipynb from this directory. Install numpy, pandas, matplotlib, scipy and notebook. The notebook uses the included Treasury CSV offline and regenerates advanced_results, including dated forecast predictions, validation metrics, PCA stability and bond stress P&L. The baseline dashboard visualises the original study only.

## Original study
# US Treasury yield curve project

Start with **Yield_Curve_Report.pdf** for the findings. Open **Yield_Curve_Analysis.ipynb** to inspect the executed analysis, calculations and embedded plots.

## Run the analysis

Extract the entire ZIP before opening the notebook. From the extracted project folder, run `python -m pip install numpy pandas matplotlib notebook`, then `python -m notebook`. Open the notebook and choose Restart Kernel and Run All. The default run reads the included CSV and regenerates the tables and PNG charts in results/. Once the dependencies are installed, it runs offline.

## Data and replication

The included data/treasury_yields.csv contains all 500 published dates from the Treasury's 24 monthly par-yield tables for 2023 and 2024, with eight annual maturities. Values are quoted in percent. source_months.csv lists the underlying pages and row counts. The optional XML check in the notebook can compare the public annual feeds with this frozen snapshot. Historical revisions may change that comparison.

The results folder includes the daily fit coefficients, the maturity-level error summary, withheld-maturity predictions, PCA weights and daily scores, the eligible weekly spread changes and three figures. The report gives the method, findings and limitations.

