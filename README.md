# Ballon d'Or 2025 Nominees: Performance Analysis

## Overview

This project analyzes the performance statistics of the 2025 Ballon d'Or nominees during the 2024–2025 season. The goal of the project is to explore player characteristics and performance metrics, compare playing time across leagues and players, and examine the relationship between expected goals (xG) and actual goals scored.

The analysis was completed in Python using Jupyter Notebook as part of a DATA 200 project at Dickinson College.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

The dataset contains statistics for the 2025 Ballon d'Or nominees, including player information and performance metrics such as:

- Age, nationality, position, club, and league
- Matches, starts, and minutes played
- Goals and assists
- Expected goals (xG)
- Additional player performance statistics

## Analysis

The project includes:

- Exploratory data analysis using descriptive statistics and dataset structure inspection.
- League-level aggregation of total, median, and maximum minutes played.
- Player-level aggregation to account for players who transferred clubs during the season and therefore appeared in multiple records.
- Analysis of the age distribution of Ballon d'Or nominees.
- Comparison and ranking of nominees based on total minutes played.
- Visualization of the relationship between expected goals (xG) and actual goals scored.

## Visualizations

Three main visualizations were created using Matplotlib:

1. **Age Distribution** — A histogram examining the age distribution of the 2025 Ballon d'Or nominees.
2. **Minutes Played Ranking** — A horizontal bar chart comparing total minutes played by each nominee.
3. **Expected Goals vs. Actual Goals** — A scatter plot examining the relationship between xG and actual goals scored.

## Interpretation

- Premier League nominees recorded the highest total and maximum playing minutes among the leagues represented in the dataset.
- La Liga had the highest median playing time among its nominees.
- The nominees ranged from 17 to 35 years old, with age 25 being the most common.
- Mohamed Salah recorded the highest total playing time among the nominees in the dataset.
- Expected goals and actual goals showed a clear positive relationship among the nominees, with several high-scoring forwards meeting or exceeding their expected goal totals.

## Limitations & Future Work

The dataset only includes Ballon d'Or nominees, meaning the analysis focuses on a highly selected group of elite players and may not represent football players more broadly.

Future analysis could expand the dataset across multiple seasons, leagues, and player levels. Additional variables such as player position, shot location, team strength, injuries, shot accuracy, and conversion rate could also be incorporated. Statistical correlation analysis and predictive modeling could then be used to further investigate the relationship between expected goals and scoring performance.

## Author

**Khang Ho**  
Dickinson College
