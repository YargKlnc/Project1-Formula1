# Formula 1 Data Analysis
# by Archit Hallan, Chisom Ozoemena, Ismail Omer, Yargi Kilinc
# Project1-Group8

Mission Statement: 

Why do the top 3 winning team win within the last 20 years( what factors help the winning team). How do the below factors effect the success and the podium? This work has been divided into 4 parts as below;

- Type of contractor
- Age of driver
- Pitstop time
- Lap speed 

Main audience: Team Coach

What factors contribute into winnimg a F1 championship?
The question would be answered after looking at the following factors closely:
1. The type of Contractors (car)
2. The age of the driver
3. Role of pit stops
4. The fastest lap speed.

# Formula 1 Championship Analysis: Type of Contractor (car)

##Introduction

This section will review the most successful F1 teams based on the type of car and nationality. The type of car plays a pivotal role in determining the success of a Formula 1 team. It is a critical factor that directly impacts a team's performance on the race track.

##Dataset Preprocessing

- Combined the constructor results, constructors and races csv files
- Dropped irrelevant columns 
- Filtered data for only years on or after 2004
- Grouped by year and calculated the winning team based on total points

##Conclusion

Mercedes is the most successful contractor over the last 20 years. I was limited by the dataset available, which didn't include car specifications. The design, engineering, aerodynamics, power unit, and overall performance of the car are all essential components that can make the difference between winning and losing in the highly competitive world of Formula 1. Teams that excel in creating and fine-tuning their cars gain a significant advantage in achieving success in this premier motorsport.

# Formula 1 Championship Analysis: The Age of the Driver
This sections takes a deeper drive into looking at races after the year 2004, the amount of wins vs the age of the driver.

##Introduction

Age has an impact of the level of experiance and skill the driver has, their physical fitness, their ablility to adapt quickly to changing techonlogies and last but not least the risk taking competitive racing has. With those reason, we are looking at if driver in their 20s and 30s have more wins than drivers in other age groups.


##Dataset Preprocessing

- Merged the `driver standings`, `drivers` , and `results` from their corresponding csv file
- The mean of ages and wins were calculated and graphed 
- The top 4 winners and their age was also presented and looked into.
- Correlation test was performed to see if age had any type of impact in winning
  

##Conclusion

Many factors have an impact on the winning of F1 championships, age does have an impact but not one that causes the winning of a championship alone. The age of a driver definitely helps given the reasons stated above but not one that the team coach would need to spend a lot of time to consider when looking for a driver. 

# Formula 1 Championship Analysis: Role of Pit Stops

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Preprocessing](#dataset-preprocessing)
3. [Analysis](#analysis)
   - [Correlation Analysis](#correlation-analysis)
   - [ANOVA Analysis](#anova-analysis)
   - [Visual Representation](#visual-representation)
4. [Implications and Recommendations](#implications-and-recommendations)
5. [Limitations](#limitations)
6. [Future Work](#future-work)
7. [Conclusion](#conclusion)

## Introduction
In the high-paced, intensely competitive world of Formula 1, a myriad of factors contributes to winning a championship. Among these, pit stops are a vital yet often underestimated element. By diving deep into detailed datasets, this analysis aims to underscore the significance of pit stop durations in race outcomes.

## Dataset Preprocessing
- Unified the pit_stops and results datasets on raceId and driverId.
- Translated time values from milliseconds to seconds for enhanced readability.
- Excluded irrelevant columns, ensuring a streamlined and concentrated analysis.

## Analysis
### Correlation Analysis
- Unearthed a modest positive correlation of ~0.33 between pit stop durations and race outcomes.
- This suggests that while pit stop times can influence race results, they are by no means the solitary decisive factor.

### ANOVA Analysis
- Delved into understanding if pit stop durations varied among different constructors.
- Found significant disparities among constructors, affirmed by a p-value close to 3.74e-23. This insight alludes to strategic variances across teams.

### Visual Representation
- A scatter plot illuminated the correlation between pit stop duration and race result duration, helping visualize individual data points and potential outliers.
- A box plot delineated pit stop duration variations across constructors, highlighting the differences in strategies and execution efficiencies.

## Implications and Recommendations
Given our findings, teams might consider:
- Re-evaluating and refining their pit stop strategies, especially if they're lagging compared to competitors.
- Investing in training and technology to minimize pit stop times, potentially gaining a competitive edge.

## Conclusion
In the intricate ballet of Formula 1 races, pit stops, though brief, play a pivotal role. While not the sole determinant, optimizing pit stop times can offer teams an edge in their overarching quest for championship glory.

# Formula 1 Championship Analysis: The Fastest Lap Speed

##Introduction

This section will review the fastest lap speeds that F1 teams reached since past 20 years. Reaching higher lap speeds might be a critical factor that will effect the final podium positions. 

##Dataset Preprocessing

- Read and merged the result, races, lap times, drivers, circuits, constructors and driver standings csv files
- Dropped irrelevant columns and filtered data for only years on and after 2004
- Created a data frame with top 10 fastest lap speeds after 2004 using nlargest&max and sorted from maximum to minimum
- Calculated the correlations between podium positions and the highest lap speeds for the 2 races that holds fastest lap speeds since 2004  

##Visual Representation
- A scatter plot illuminated the correlation between fastest lap speeds and final positions for the 2 races that holds the highest lap speeds that will help visualize individual data points and potential outliers.
- Correlation value represented on scatter plots

##Conclusion
Ferrari team keeps the 2 highest lap speeds reached since past 20 years followed by McLaren team. This analysis is limited to the dataset available and there are other factors that will effect the final podium positions. Looking into races with record highest lap speeds in the past 20 years and the negative correlation with the final positions, it is possible to say that reaching the highest speeds in a lap likely results with a place in the podium as a finalist in first 3.

https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020?select=constructors.csv

https://www.kaggle.com/code/ameyabhagat24/da-on-f1#Data-Analysis-on-Formula-1

