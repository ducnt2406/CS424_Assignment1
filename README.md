# CS 424 Assignment 1

## Task 1: Observation and Data Collection
- I chose to observe the occupancy of Richard J. Daley Library because I have been there almost every day, and I am interested in how the occupancy of the two main public floors changes at the same crowded time (4 pm) from Monday to Friday. The project focuses on public areas of the 1st and 2nd floors and excludes private rooms. Observations were made at approximately 4 pm to ensure consistent collection from Monday to Friday.
- One observation represents one manual occupancy count of one floor. For each observation, I recorded the date, time, approximate occupancy count by my method, estimated noise level based on my hearing, and the optional notes when my counting accuracy was affected by high movement. Because this project was done by me alone, all observations were collected by me using the same general procedure.
- To make my counting process more manageable, I divide each floor into sections, count the occupants in each section, and calculate the sum to estimate the total occupancy of each floor. Each occupant was counted as 1, and a fully occupied four-seat table was counted as 4 to simplify the count.
- The collection provides the variation across location (1st and 2nd floor), date, and observations collected from Mondays to Fridays. I know the design has many limitations: the private room is inaccessible, and observations were made only at approximately 4 pm because that is the only time I don't have any classes throughout the week. Therefore, the data doesn't represent library occupancy for the entire day. My manual counting process may also miss or double-count occupants who enter, leave, or move between sections. In addition, the noise level measurement is based on my personal feeling rather than an objective sound measurement.

 
## Initial Question
1. Difference between the occupancy of the 1st floor and the 2nd floor at 4 pm? 
2. Do occupancy on the 1st floor and 2nd floor change in a similar trend across 5 days?
3. How does the perceived noise level relate to the occupancy?
4. Which days have the highest and lowest occupancy in the week?


| Attribute | Type | Description | Example |
|---|---|---|---|
|date|Temporal|Date of observation|9/21/2026|
|time|Temporal|Time of observation|4 pm|
|floor|Categorical|Observed library floor|1st|
|occupancy_count|Quantitative|Approximate number of occupancy|53|
|noise_level|Ordinal|Overall perceived noise level of the floor|Quiet|
|notes|Text|Optional notes|High movement|


## Task 2: Pilot and Data Collection

### Pilot collection
- From Monday 9/21 to Friday 9/25, each day I collected 2 pilot observations of the 1st and 2nd floor. In each observation, I counted the total number of occupants in the floor's public area. To make this task easier, I counted the number of fully table and the number of individuals, then calculated the total occupants using the formula: individuals + fully table * 4. Because some people could move while I was counting, the occupancy result should be treated as approximate only. 

### Pilot reflection and revisions
- The pilot showed that the 1st floor was easy to count because of its small area, while the 2nd floor was more complicated than I expected because the public area is much larger and more crowded. Sometimes the noise distracted me when I was counting. 
- To improve the consistency, I divided the 2nd floor into small sections and applied this method to all the 2nd floor's observations. This made the process more manageable, especially on the 2nd floor, even though I knew that an error could occur because some occupants were moving between sections. 
- The noise_level attribute was difficult to estimate consistently, although I estimated it by Decibel X, the number of each measurement attempt was heavily affected by the crowd. To make it more systematic, I defined 3 ordered levels: Quiet, Moderate, Noisy.


## Task 3: Data description and Domain questions

### Dataset description
- The final dataset contains 10 observations collected across 5 days from the public area of Richard J. Daley Library at approximately 4 pm. Each observation records the date, floor, approximately occupancy count, noise level, and optional notes. 
- Occupancy was measured manually by dividing each floor into sections and adding them together to find the final number of occupants. The dataset captures variation between two floors and across 5 days (9/21-9/25). However, it doesn't represent occupancy at other times of day or in a private room. 
- Because occupants could enter, leave, or move around the area during the counting process, the occupancy values should not be treated as 100% correct. 

### Reflection on the Data
- The dataset captures the approximate number of occupants present on the 1st and 2nd Floors, the date and time of observation, and the general noise level. This makes it possible to compare occupancy on the 1st and 2nd Floors and examine how it changes over 5 days. 
- However, the dataset couldn't capture who the occupants are (students, staff, professors, or TAs), the reason why they are in the library, and how long they stay. It also doesn't represent the occupancy in a private area. Because the counts were collected manually while people were moving, some occupants may have been missed or counted twice. 

### Final domain questions

## Task 4: Task abstractions

## Task 5: Visualization Sketches

## Task 6: Summarizing 

## Task 7: Collaboration Process

