# Road Pothole Severity Assessment — EDA

**Student:** Jayanan M  
**Branch:** Computer Science and Engineering

## Objective
Complete Exploratory Data Analysis of road-pothole detection and severity records.

## Dataset note
The included CSV is a **synthetic educational dataset** created for reproducible EDA practice. It follows the documented feature structure and severity bands of the public IPDS pothole field-test project, but its individual rows are generated and are **not the original field observations**.

The referenced public project documents a 50-detection sample with Low/Medium/High severity bands and peak-jerk ranges of 1.6–2.7, 3.0–5.9 and 6.0–9.4.

## Repository structure
```text
Road-Pothole-Severity-EDA/
├── Assignment1_EDA_Jayanan_RoadPotholeSeverity.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── road_pothole_severity_eda.csv
└── outputs/
    ├── missing_values.png
    ├── severity_distribution.png
    ├── numerical_distributions.png
    ├── boxplots.png
    ├── correlation_heatmap.png
    ├── severity_vs_measurements.png
    ├── pairplot.png
    └── outlier_summary.csv
```

## EDA performed
Dataset inspection, missing-value analysis, duplicate detection, invalid-value checking, cleaning, IQR outlier analysis, descriptive statistics, univariate analysis, severity distribution, bivariate analysis, correlation heatmap, severity comparisons, multivariate pair plot, findings and conclusion.

## Run
```bash
pip install -r requirements.txt
jupyter notebook Assignment1_EDA_Jayanan_RoadPotholeSeverity.ipynb
```

The notebook can also be uploaded directly to Google Colab.

## Academic limitation
Because the included CSV is synthetic, the numerical findings are an EDA demonstration and should not be presented as new empirical road-safety findings.
