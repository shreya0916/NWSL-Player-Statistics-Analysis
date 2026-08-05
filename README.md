# NWSL-Player-Statistics-Analysis

## Overview
This project explores player statistics across three National Women's Soccer League (NWSL) teams: Portland Thorns FC, Angel City FC, and Gotham FC. 
- Combined and cleaned player statistics from multiple teams into a single dataset for analysis.
- Performed exploratory data analysis to investigate age distributions and relationships between minutes played and goals scored.
- Created data visualizations with ggplot2 and documented the complete analytical workflow in a reproducible R Markdown report.
- Documented methodology and analysis in reproducible R Markdown reports.

1. **Age distribution of professional women soccer players**  
2. **Relationship between minutes played and goals scored**

## Data Source

Data was collected from [FBref](https://fbref.com/en/) for the most recent NWSL season. CSVs for each team are included:

- `portland_thorns_Sheet1.csv`
- `angel_city_Sheet1.csv`
- `gotham_mc_Sheet1.csv`

## Files

- `NWSL_analysis.Rmd`: R Markdown file containing all analysis and plot generation.  
- `player_age_distribution.png`: Histogram of player ages.  
- `goals_vs_minutes.png`: Scatter plot of goals vs minutes, highlighting Angelina Anderson.  
- `Project1_Reflection.pdf`: Reflection on Project 1.

## How to Reproduce

1. Clone the repository.  
2. Open `NWSL_analysis.Rmd` in RStudio.  
3. Run all code chunks to regenerate the plots.  
4. Alternatively, the plots are already saved as PNGs in the repository.

