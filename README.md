# Baby Sleep Analysis

This project allows you to create multiple analyses and visualizations of your baby's sleep data. It focuses on the following metrics:

1. The length of your baby's longest sleep periods
2. Daytime and nighttime sleep distributions
3. Total sleep amounts
4. How early into the evening nighttime sleep begins

Sample copies of some of the interactive charts created by this script can be found [on this Google Sites](https://sites.google.com/view/sample-baby-sleep-charts/home) page. Here are static copies of those charts:

<img src="https://raw.githubusercontent.com/kburchfiel/baby_sleep_analysis/main/Visualizations/longest_sleep_periods_by_day_scatter.png" width = "600" />

<img src="https://raw.githubusercontent.com/kburchfiel/baby_sleep_analysis/main/Visualizations/weekly_total_sleep_by_period.png" width = "600" />

<img src="https://raw.githubusercontent.com/kburchfiel/baby_sleep_analysis/main/Visualizations/weekly_avg_hours_after_onset.png" width = "600" />

<img src="https://raw.githubusercontent.com/kburchfiel/baby_sleep_analysis/main/Visualizations/weekly_total_sleep.png" width = "600" />

## Instructions for use:

1. Clone or download this project.

2. Overwrite the 'sleep_dataset.csv' file with your baby's sleep data. This data can come from two different sources:

    a. A .csv export of infant data from the Huckleberry app. (I have no affiliation with Huckleberry; it just happens to be the app that I use for sleep tracking purposes.)
    
    b. A custom .csv file that contains start and end times for each sleep period. (A sample version of this file can be found within 'sleep_dataset.csv'.)

    If you have a different type of app or tracker that also supports .csv exports, you should be able to modify the code so that it supports whatever sleep data format it happens to use. You'd just need to get your own data to match the formats and fields shown within 'sleep_dataset.csv'.

3. Open baby_sleep_analysis_v5.ipynb (or a later version of this file), then run the script. This will overwrite the sample visualizations and data output files stored in the project with your own baby's data.

**Note: by default, this notebook imports and analyzes a set of fictional sleep data stored as 'sleep_dataset.csv'. This dataset is NOT meant to indicate regular infant sleep patterns!** (To see how this table was created, open the 'Sleep Dataset Generator.ipynb' file.)