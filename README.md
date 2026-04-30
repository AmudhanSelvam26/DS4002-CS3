# DS4002 CS3: Predicting UVA-area Rent Using Employment


## Software And Platform ##
- For the software, we have used Python (v3.11.7) for all the scripts and data analysis with the following required add-on packages:
    - pandas (v3.0.1) for manipulation of .csv files into usable data frames
    - numpy (v2.4.3) for numerical operations
    - scipy (v1.17.1) for statistical tests used in the analysis
    - scikit-learn (v1.8.0) for evaluation metrics (e.g., MAE)
    - prophet (v1.3.0) for time-series modeling
    - dieboldmariano (v1.1.0) for forecast comparison (DM test)
    - pyprojroot (v0.3.0) for project-path handling
    - matplotlib (v3.10.8) and seaborn (v0.13.2) for data visualization and plotting
 - The platform used was Mac.

## A Map of Documentation

```text
MI1-2/
├── DATA/
│   ├── Charlottesville_Employment_Data.csv
│   ├── Charlottesville_Rent_Employment_Master.csv
│   └── Zillow_Rent_Data.csv
│
├── OUTPUT/
│   ├── eda_1_rent_trend.png
│   ├── eda_2_employment_trend.png
│   ├── eda_3_dual_axis_comparison.png
│   ├── eda_4_scatter_plot.png
│   └── eda_5_monthly_boxplot.png
│
├── SCRIPTS/
│   ├── analysis.ipynb
│   ├── data_extraction.py
│   └── eda.py
├── README.md
```
