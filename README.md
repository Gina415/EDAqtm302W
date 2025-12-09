# Sleep & Mental Health Outcomes in U.S. Adults (NHIS): An Exploratory Data Analysis

## Authors
Christina Fu & Gina Ge, Emory University ENGRD/QTM 302W

## Project Objective
This project conducts an exploratory data analysis (EDA) of the 2024 National Health Interview Survey (NHIS) Sample Adult dataset to understand patterns in adult health outcomes. Our project focuses on working adults aged 25–55 and examines patterns linking sleep duration, sleep quality, to mental-health indicators, including depression, anxiety, psychological distress, and emotional wellbeing.

### Methods Used
* Descriptive Statistics
  * summary
  * table
* Data Cleaning
  * stringr
  * dplyr
  * tidyr
* Data Visualization
  * ggplot2 - bar charts, histograms, scatter plots, box plots, etc.
  * ggcorplot - correlation matrix
* Correlation/Statistical Analysis
  * Kruskal-Wallis test
  * Pairwise Wiloxcon rank sum test
  * Linear modeling
  * Spearman's rank correlation coefficient

### Technologies
* R/RStudio
  * Markdown
  * tidyverse
* GitHub

## Project Description
This project analyzes a subset of the 2024 NHIS to explore how sleep quality relates to mental health among working U.S. adults 25-55 years. The NHIS is a nationally representative survey conducted annually by the National Center for Health Statistics, providing comprehensive information on health status, behaviors, and socioeconomic demographics.
We extracted variables from the adult questionnaire related to:
* Sleep behaviors (e.g. hours slept, feeling well-rested, trouble falling/staying asleep, sleep-related medication use)
* Mental health conditions (e.g. anxiety/depression diagnosis, medication/therapy usage, emotional distress indicators)

### Research Questions
We were interested in investigating whether sleep duration and sleep quality are meaningfully associated with levels of psychological distress, and whether these sleep patterns differ among individuals diagnosed with anxiety and/or depression. We restricted our sample to adults ages 25-55 years due to minimal prior research conducted on mental health outcomes in working-aged adults which also helped us reduce any age-related variation that may occur in our variables-of-interest. We evaluated relationships between hours slept and severity of psychological distress, sleep difficulties and anxiety/depression diagnoses, and more.

### Models and Visualizations
* Grouped comparisons (both cateogrical and quantitative)
* Regression and non-parametric testing of sleep–distress associations
* Correlation matrices of sleep variables compared to mental health variables
* Stacked & side-by-side barcharts of data distributions

### Challenges
* Utilizing appropriate correlation and regression analyses for nonparametric datasets to build comprenhensive findings
* Ensuring visualizations illustrate meaningful patterns
* Managing variable formats (categorical vs. continuous formats, missingness, ambiguous survey codes)

### Future Directions
* Stratified analyses to control confounding variables
* Repeat analyses on respondents that make up outliers (e.g. very little or excessive sleep duration, high psychological distress score)
* Determine causation and directionality of association between sleep patterns and mental health outcomes

## Getting Started
1. Clone this repository.
2. Raw data is being kept in ./EDAqtm302W/data/adult24.csv within this repository
3. Processed data is kept in ./EDAqtm302W/data/adult_selected.csv
4. Data processing and main code notebook scripts are being kept in ./EDAqtm302W/
5. Install required packages

## Directory Structure
.
└── EDAqtm302W/
    ├── Data/
    │   ├── adult24.csv
    │   └── adult_selected.csv
    ├── new_EDA_Project.Rmd
    └── README.md

## Contact
**Christina Fu (christina.fu@emory.edu)**
**Gina Ge (gina.ge@emory.edu)**