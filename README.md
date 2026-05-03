# DS4002 CS3: Predicting UVA-area Rent Using Employment



## Introduction

- **You are given:** materials in `MATERIALS/`, starter CSVs in `DATA/`, the hook (`CS3 Hook Amudhan Selvam-2.pdf`), and the rubric (`CS3 Rubric Amudhan Selvam.pdf`).
- **You produce:** everything in `CS3 Rubric Amudhan Selvam.pdf` - cleaned analysis data, the data appendix, `LICENSE.md`, code in `SCRIPTS/`, outputs in `OUTPUT/`, and the README sections below filled in with your workflow, results, and reflection.

## Software and platform

- **Language:** Python (example: 3.11.x).
- **Packages used (typical packages; replace with what you used, including version numbers):** pandas, numpy, scipy, scikit-learn, prophet, dieboldmariano (optional, for forecast comparison), pyprojroot (optional, for paths), matplotlib, seaborn.
- **Platform:** Any OS that runs the above; document what you used.

## A map of documentation

```text
DS4002-CS3/
├── DATA/
│   ├── Charlottesville_Employment_Data.csv
│   └── Zillow_Rent_Data.csv
│
├── OUTPUT/ (create if missing from git clone)
│   └── (add your generated figures, tables, and other outputs here)
│
├── SCRIPTS/ (create if missing from git clone)
│   └── (add your data prep, EDA, and modeling code or notebooks here)
│
├── MATERIALS/
│   ├── Getting Started Predicting Time Series Data with Facebook Prophet | by Jonas Dieckmann | TDS Archive | Medium.pdf
│   ├── research-notes-12-10-25.pdf
│   └── 3190.pdf
├── CS3 Hook Amudhan Selvam-2.pdf
├── CS3 Rubric Amudhan Selvam.pdf
└── README.md
```

When you finish the case study, also add to `DATA/` whatever **final analysis dataset(s)** and **data appendix** the rubric asks for (`CS3 Rubric Amudhan Selvam.pdf`).

## Instructions for reproducing your results

Complete this section for **your** repository so someone else can go from the starter CSVs to your conclusions. At minimum, address:

1. **Data:** How you joined the rent and employment data (e.g., frequency, geography, date keys), handled missing values, and constructed the final analysis dataset. Point to the scripts that perform each step.
2. **EDA:** What you plot to explain modeling choices and better understand the data provided.
3. **Modeling:** How you fit a baseline Prophet model on rent only, then a model with Charlottesville employment as a regressor (and any lags or events you encode). State how you measure error (e.g., MAE on a reserved test period) and, if you went for the additional challenge, how you measured the “5% better than baseline” requirement from the rubric.
4. **Outputs:** Which figures or tables in `OUTPUT/` support your main claims.


## Written summary, lessons learned, and tips for future work

Summarize what you found about rent and employment near UVA, whether the regressor helped, and what you would try next (alternative regressors, different models, other metrics).

## References

List every source you cite (including course materials, documentation, and data providers) in IEEE style.
