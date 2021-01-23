# matplotlib-pharmaceutical-analysis
Analysis using matplotlib and pandas of pharmaceutical data


## Getting Started

Repository contains:
- A jupyter notebook file with all analyses and summary insights (pharmaceutical-analysis.ipynb)
- Two csv files used in the analysis (Mouse_metadata.csv and Study_results.csv)

The jupyter notebook contains additional details of the analysis


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

### Bar and Pie Charts -
- There are two versions of each chart:
  - One uses pandas.plot and the other uses matplotlip.pyplot
- Bar charts show total count of measurements for each of the 8 treatment groups
- Pie charts show the distribution of female and male mice in the study

### Quartiles, Outliers, and Boxplots
- Qunatitative investigation of potential outliers based on final measurement of tumor volume (mm3)
  - Analysis looks at tumor volume at last timepoint for mouse per 4 treatment groups of interest
  - Includes count of potentual outliers
  - Box plot of final tumor volume with outlier noted as a blue star

### Line and Scatter Plots
- Line chart of a single mouse example treated with Capomulin
  - Chart is number of days by tumor volume


## Licensing by:

The code in this project is licensed under MIT license.
