# Project1-Group8

Main question:
What factor plays in winning a F1 championship? Why do the top 3 winning team win within the last 10 years( what factors help the winning team)

Sub questions: pit stop time, type/age of driver, the type of contractors (type of brand of car), lap-time (does not mean you will win the season/game), see the percentage of nationality and see how their nationalities plays a role

Main audience: Team Coach

Structure: find the mean for all teams, and the mean between the top winning team and the correlation between the data and the winning team. Use bar chart, pie chart or line/scatter plot to show the mean, mean between the top 3 and the correlation

(archit - pit stop time, chisom- age of driver, yargi- lap time, ismail- type of contractor)

# Formula 1 Championship Analysis: Role of Pit Stops

This section of the larger project dives deep into understanding how pit stop durations influence outcomes in Formula 1 races, contributing to winning a championship.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Preprocessing](#dataset-preprocessing)
- [Analysis](#analysis)
  - [Correlation Analysis](#correlation-analysis)
  - [ANOVA Analysis](#anova-analysis)
- [Visual Representation](#visual-representation)
- [Conclusion](#conclusion)

## Introduction

Within the multifaceted world of Formula 1, various factors contribute to winning a championship. This segment focuses on one such crucial aspect: pit stops. By analyzing detailed datasets, we seek to understand the strategic implications of pit stop durations.

## Dataset Preprocessing

- Merged the `pit_stops` and `results` datasets based on `raceId` and `driverId`.
- Time values converted from milliseconds to seconds for better clarity.
- Columns not pertinent to pit stops were removed to ensure focused analysis.

## Analysis

### Correlation Analysis

- Established a weak positive correlation (~0.08) between pit stop durations and race outcomes. 
- This correlation suggests pit stop times might influence the race outcome, but are not the sole determinants.

### ANOVA Analysis

- The goal was to understand if different constructors have varying pit stop durations.
- Significant differences were found among constructors with a p-value approximating 3.74e-23.

## Visual Representation

- A scatter plot depicted the relationship between pit stop duration and race result duration.
- A box plot showcased variations in pit stop durations across different constructors, emphasizing strategic differences.

## Conclusion

While numerous factors play a role in determining a Formula 1 championship winner, pit stops undoubtedly have their strategic importance. Though they are not the singular pivotal factor, optimizing pit stop durations can provide teams with a competitive edge in the overarching journey to clinch the championship title.


https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020?select=constructors.csv

https://www.kaggle.com/code/ameyabhagat24/da-on-f1#Data-Analysis-on-Formula-1

