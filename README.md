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
    - One contains the duplicates (duplicate_mouse_df)
    - Another excluding them which is used for all further analyses (mouse_study_clean)


## Licensing by:

The code in this project is licensed under MIT license.
