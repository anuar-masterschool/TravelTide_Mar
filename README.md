# Travel Tide Project
Short summary of the project.

## Overview:
- Goal
- what was done
- results 


## Structure:
```
├── data
│   ├── groups
│   │   ├── family_traveler.csv
│   │   ├── low_income.csv
│   │   ├── luxus.csv
│   │   ├── no_bookers_group.csv
│   │   ├── overcarriers.csv
│   │   ├── seniors.csv
│   │   ├── singles.csv
│   │   └── young.csv
│   ├── processed
│   │   ├── hotels_pocessed.csv
│   │   ├── user_features.csv
│   │   └── users_no_group.csv
│   ├── raw
│   │   ├── flights_raw.csv
│   │   ├── hotels_raw.csv
│   │   ├── sessions_raw.csv
│   │   └── users_raw.csv
│   └── tables_filtering.sql
├── notebooks
│   ├── 1_EDA.ipynb
│   ├── 2_users_feature_engineering.ipynb
│   ├── 3_user_segmentation.ipynb
│   ├── 4_ml_clustering.ipynb
│   └── 5_result.ipynb
├── README.md
├── requirements.txt
└── results
    ├── excecutive_summary.pdf
    ├── fig
    │   └── pairplot_analysis.png
    └── users_with_groups.csv
```

## Setup:
1. Install dependencies (requirements.txt)
2. In data/tables_filtering.sql use the data string and run the 4 queries and save the results in data/raw as hotels_raw.csv, users_raw.csv ...
3. Run notebooks in order

## Notebooks description:
- 1_EDA.ipynb:  

