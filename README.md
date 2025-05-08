# Heart Disease Mortality Prediction Using Socioeconomic and Health Data

This project explores how demographic, economic, and health-related indicators predict heart disease mortality across U.S. counties. Combining statistical analysis and machine learning, it identifies key health and economic factors that contribute to regional differences.

🌐 [View Project Page](https://winston-wang.com/portfolio/heart-disease-data-analysis/)

## Project Structure

- `data/` — Raw and processed datasets
- `scripts/` — Data integration, cleaning, and modeling scripts
- `output/` — Generated figures, model summaries, and results

##  Technology Stack

- **Programming Language**: R
- **Libraries**: tidyverse, ggplot2, glmnet, psych, corrplot, lattice
- **Methods**: LASSO Regression, PCA, Factor Analysis, LDA

##  Dataset Description

The dataset includes 1,069 U.S. counties with 23 features, covering health behaviors, economic conditions, demographics, and geographic classifications. Data sources include the USDA Economic Research Service, CDC, U.S. Census, and Bureau of Labor Statistics.

##  Methodology Overview

- Data cleaning and feature transformation
- Exploratory data analysis with correlation plots
- LASSO regression for feature selection
- PCA and factor analysis for dimensionality reduction
- LDA for classification of county typologies

## Results and Impact

- LASSO identified key predictors like obesity, smoking, and diabetes
- PCA captured ~70.7% variance with 4 components
- LDA classification achieved up to 73.2% accuracy
- Predictive models reveal strong links between health behaviors and heart disease mortality

## Project Tree

```
heart-disease-data-analysis/
├── .gitignore
├── LICENSE
├── README.md
├── data/
│   ├── README.md
│   ├── processed/
│   └── raw/
├── output/
│   ├── README.md
│   ├── figures/
│   └── results/
└── scripts/
    ├── README.md
    ├── 0_data_integration.R
    ├── 1_missing_value_analysis.R
    ├── 2_analysis.R
    └── utilities/
        └── confusion_function.R
```

---

**License**: MIT License © Winston Wang
