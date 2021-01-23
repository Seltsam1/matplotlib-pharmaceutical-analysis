# matplotlib-pharmaceutical-analysis
Analysis using matplotlib and pandas of pharmaceutical data


## Getting Started

Repository contains:
- A jupyter notebook file with all analyses and summary insights (pharmaceutical-analysis.ipynb)
- Two csv files used in the analysis (Mouse_metadata.csv and Study_results.csv)


## Features

### Cleaning -
- Code will merge two csv files into a single dataframe (mouse_study_df)
- Finds if any mice in the study have identical timestamps
  - Creates two new dataframes:
    - Contains only the duplicate data for reference (duplicate_mouse_df)
    - Excludes the duplicate data, used for further analyses (mouse_study_clean)

### Summary Statistics -
- Tables of summary statistics: 
  - Mean, median, variance, standard deviation, and sem (standard error of the mean)
- Includes two methods:
  - Pandas approach
  - Aggregation method using numpy and scipy


## Licensing by:

The code in this project is licensed under MIT license.
