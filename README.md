# NYC Subway Fare Burden Analysis

This project aims to analyze the fare burden and transit equity in New York City, using various datasets such as subway ridership data and census data. The goal is to understand how different demographic groups are impacted by subway fares and identify potential disparities in fare burden.

## Folder Structure
├── data # Data files (raw and processed)
│ ├── processed # Processed and cleaned data
│ ├── raw # Raw, unprocessed data
├── notebooks # Jupyter notebooks with analysis and modeling
├── results # Final results and presentation
└── README.md # Project documentation

## Data Sources

1. **MTA Subway Hourly Ridership (2023)**: Hourly ridership data for New York City subway stations.
2. **NYPD Arrests Data**: Data on arrests made by the NYPD, specifically for fare evasion.
3. **American Community Survey (ACS) 2023**: Demographic and income data from the U.S. Census Bureau, used to analyze socio-economic factors.

## Key Files and Notebooks

- **`data/processed/`**: Cleaned and merged data, including ridership, arrest data, and demographic information.
- **`data/raw/`**: Original datasets including subway ridership, NYPD arrests, and ACS data.
- **`notebooks/`**: Jupyter notebooks for analysis and modeling.
    - **`Analysis_CENSUS.ipynb`**: Analysis of census data and its impact on fare burden.
    - **`Analysis_DiscreteBayesianNetwork.ipynb`**: Exploration of Bayesian network models for anomaly detection.
    - **`Model_Transit Disparities.ipynb`**: Machine learning models used to analyze transit disparities.
- **`results/`**: Final outputs of the analysis, including visualizations and presentations.

## Project Workflow

1. **Data Collection and Preprocessing**: Raw data is collected and processed into clean datasets. This includes merging various datasets such as ridership data, NYPD fare evasion arrests, and ACS demographic data.
   
2. **Exploratory Data Analysis (EDA)**: Initial analysis and visualization to identify patterns and trends in the data, including how different demographic groups interact with the subway system.

3. **Modeling**: Machine learning models are developed to predict and analyze fare burden, and to identify anomalies and disparities across different groups.

4. **Results**: A final analysis of fare burden and transit equity is presented through both statistical analysis and machine learning models.
