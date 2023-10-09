# Project1-Group8

Main question:
What factor plays in winning a F1 championship? Why do the top 3 winning team win within the last 10 years( what factors help the winning team)

Sub questions: pit stop time, type/age of driver, the type of contractors (type of brand of car), lap-time (does not mean you will win the season/game), see the percentage of nationality and see how their nationalities plays a role

Main audience: Team Coach

Structure: find the mean for all teams, and the mean between the top winning team and the correlation between the data and the winning team. Use bar chart, pie chart or line/scatter plot to show the mean, mean between the top 3 and the correlation

(archit - pit stop time, chisom- age of driver, yargi- lap time, ismail- type of contractor)

## Formula 1 Pit Stop Analysis

This repository contains a comprehensive analysis of the impact of pit stop durations on Formula 1 racing outcomes.

### Table of Contents
- [Introduction](#introduction)
- [Dataset Preprocessing](#dataset-preprocessing)
- [Analysis](#analysis)
  - [Correlation Analysis](#correlation-analysis)
  - [ANOVA Analysis](#anova-analysis)
  - [Visual Representation](#visual-representation)
- [Conclusion](#conclusion)
- [Visualizations](#visualizations)
- [Usage](#usage)
- [Contributions](#contributions)

### Introduction
The core objective of this project is to explore the extent to which pit stop durations impact race outcomes in Formula 1. Using detailed datasets, we delve deep into various analytical techniques to unravel this relationship.

### Dataset Preprocessing
- Merged `pit_stops` and `results` datasets based on `raceId` and `driverId`.
- Time values were converted from milliseconds to seconds.
- Irrelevant columns were systematically removed to streamline the data for analysis.

### Analysis

#### Correlation Analysis
- Determined a weak positive correlation of approximately 0.08 between pit stop durations and race results.
- This weak correlation suggests that while pit stop times might influence the race outcome, other factors also play a crucial role.

#### ANOVA Analysis
- Analyzed if different constructors had significantly varying pit stop durations.
- The findings, with a p-value of around 3.74e-23, confirmed that pit stop durations significantly differ among constructors.

#### Visual Representation
- Utilized a scatter plot to illustrate the relationship between pit stop duration and race result duration.
- Employed a box plot to visually represent pit stop duration variations across different constructors.

### Conclusion
The in-depth analysis underscores the significance of pit stop durations in Formula 1 racing. While pit stop times play a role, they are just one of many factors influencing race outcomes. Nevertheless, the substantial variation in pit stop durations among constructors implies a strategic element that teams can potentially optimize for better results.



https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020?select=constructors.csv

https://www.kaggle.com/code/ameyabhagat24/da-on-f1#Data-Analysis-on-Formula-1

