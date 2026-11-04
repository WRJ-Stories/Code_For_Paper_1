# Gut-microbiome-signatures-combined-with-stool-SDC2-methylation-for-colorectal-cancer-detection
Analysis code and figure source data for an integrated gut microbiome and stool SDC2 methylation study in colorectal cancer, including metagenomic analysis, feature selection, Bayesian modeling, microbial network analysis, and diagnostic model development.

## Repository Structure

The repository is organized into two main archives: `scripts.zip`, containing the analytical source code, and `FigureData.zip`, containing the source data underlying all figures presented in the manuscript.

```text
Code_For_Paper_1/
│
├── README.md
│
├── scripts.zip
│   ├── classification/
│   │   ├── crc_msd2_microbiome_nested_analysis.R
│   │   └── crc_msd2_performance_improvement_analysis.R
│   │
│   ├── differential/
│   │   ├── lefse_analysis.R
│   │   └── maaslin3_analysis.R
│   │
│   ├── dki_keystoneness/
│   │   ├── dki_calculate.py
│   │   └── Keystoneness_computing.R
│   │
│   ├── feature_selection/
│   │   ├── bayesian_regression.R
│   │   ├── importance_scoring.R
│   │   ├── lasso_regression.R
│   │   ├── mrmr_panel_core.R
│   │   ├── mrmr_screening.R
│   │   └── random_forest_shap_analysis.R
│   │
│   ├── meta_analysis/
│   │   └── ap_clr_meta_analysis.R
│   │
│   └── microbial_network/
│       └── network_module_analysis.R
│
└── FigureData.zip
    └── Source data underlying all manuscript figures
```

### Analysis Modules

| Directory | Description |
|---|---|
| `classification/` | Nested cross-validation, diagnostic model development, and model performance evaluation. |
| `differential/` | Differential microbiome analysis using LEfSe and MaAsLin3. |
| `dki_keystoneness/` | Calculation and analysis of microbial structural keystoneness. |
| `feature_selection/` | Feature selection and importance assessment using Bayesian regression, LASSO, random forest–SHAP, and mRMR. |
| `meta_analysis/` | Meta-analysis of adenoma-associated microbial features based on CLR-transformed abundance data. |
| `microbial_network/` | Microbial interaction network construction and module-level analysis. |

The analysis scripts are grouped by analytical function to facilitate navigation and reuse.

## Figure Data

The `FigureData.zip` archive contains the source data underlying all figures presented in the manuscript, including the main figures and supplementary figures.

These files provide the numerical data used to generate the corresponding visualizations and are intended to facilitate data inspection, verification of reported results, and reproduction of the figures.

The archive is provided separately from the analytical scripts to keep the repository organized and facilitate access to figure-related data.

To access the figure source data, download and extract `FigureData.zip` from the repository.
