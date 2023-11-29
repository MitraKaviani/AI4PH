# AI4PH Final Assignment 
## Mortality Trends Analysis (1980-2019)
Overview

This analysis is conducted on a dataset derived from death certificates to compare mortality data between 1980 and 2019. The dataset is structured to highlight significant trends in mortality, causes of death, and their evolution over nearly four decades.
Dataset Structure

    Data Source: Death certificates
    Time Frame: 1980 and 2019
    Columns: Age and rank order, cause of death, number of deaths for both 1980 and 2019

Note: The first few rows contain headers and explanatory notes. The actual data starts further down, necessitating an adjustment in data loading.
Objective

    To analyze trends in mortality over time.
    To identify major health risks and causes of death.
    To inform public health policy and healthcare priorities.

Analysis Steps

    Data Loading and Cleaning:
        Load the dataset, skipping initial explanatory rows.
        Rename columns for clarity.
        Handle missing values (either by dropping or filling with a default value).
        Ensure correct data types for analysis.

    Data Analysis:
        Perform exploratory data analysis, including summary and descriptive statistics.
        Compare mortality rates over time and across different age groups.
        Identify top causes of death in 1980 and 2019 and their trends.

    Visualization:
        Plot key findings, such as top causes of death and changes in mortality rates by age group.

    Insights and Conclusions:
        Summarize key trends and insights.
        Discuss implications for public health and policy-making.

Tools Used

    Python (Pandas for data manipulation, Matplotlib for visualization)

Note to Users

    Replace the file path in the script with the actual path to your dataset.
    Adjust the number of skipped rows (skiprows) based on your dataset's structure.
    The code provided is a starting point; further customization may be needed based on specific analysis goals.
