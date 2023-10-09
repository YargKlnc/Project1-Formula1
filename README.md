# Project1-Group8
Main audience: Team Coach
What factors contribute into winnimg a F1 championship?
The question would be answered after looking at the following factors closely:
1. The type of Contractors (car)
2. The age of the driver
3. Role of pit stops
4. The fastest lap speed.

# Formula 1 Championship Analysis: The Age of the Driver
This sections takes a deeper drive into looking at races after the year 2004, the amount of wins vs the age of the driver.

#Introduction
Age has an impact of the level of experiance and skill the driver has, their physical fitness, their ablility to adapt quickly to changing techonlogies and last but not least the risk taking competitive racing has. With those reason, we are looking at if driver in their 20s and 30s have more wins than drivers in other age groups.


#Dataset Preprocessing

- Merged the `driver standings`, `drivers` , and `results` from their corresponding csv file
- The mean of ages and wins were calculated and graphed 
- The top 4 winners and their age was also presented and looked into.
- Correlation test was performed to see if age had any type of impact in winning
  

# Conclusion
Many factors have an impact on the winning of F1 championships, age does have an impact but not one that causes the winning of a championship alone. The age of a driver definitely helps given the reasons stated above but not one that the team coach would need to spend a lot of time to consider when looking for a driver. 

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

