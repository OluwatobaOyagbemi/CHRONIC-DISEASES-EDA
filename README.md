# CHRONIC-DISEASES-EDA
Learning-focused exploratory data analysis of chronic disease indicators using Python
# Overview
This repository contains a learning-focused exploratory data analysis (EDA) project using data.gov publicly available chronic disease indicator data across the United States.

The primary objective of this project is to strengthen skills in data cleaning, exploratory analysis, visualization, and responsible interpretation of real-world public health data.

## Dataset Notes
- Original dataset size: 209,196 rows × 34 columns
- I used the .info() method form python`s libraryto get the summary of DataFrame.
- Refined dataset: 209,196 rows × 29 columns
- Proceeded to use the .dropna() to remove redundant columns.[eda_analysis.ipynb](https://github.com/user-attachments/files/24725624/eda_analysis.ipynb)
[eda_analysis.ipynb](https://github.com/user-attachments/files/24725619/eda_analysis.ipynb)
[eda_analysis.ipynb](https://github.com/user-attachments/files/24725615/eda_analysis.ipynb)

- Several columns were removed due to high missingness, redundancy, or limited analytical value
- The dataset contains aggregated indicators and mixed measurement definitions

## Key Insights
- Visualizations reveal variation in chronic disease indicators across categories, locations, and time.
- Aggregation limits direct interpretation of prevalence
- Patterns are descriptive and exploratory, not predictive or clinical

## Methodological Considerations
A machine learning extension was evaluated; however, predictive modeling was not statistically appropriate due to aggregated values, inconsistent measurement scales, and unclear target definitions.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Disclaimer
This project is exploratory and learning-oriented. Results are descriptive and should not be interpreted as precise prevalence estimates or predictive outcomes.



