# CS 424 Assignment 1

## Task 1: Observation and Data Collection
- I chose to observe the occupancy of Richard J. Daley Library because I have been there almost every day, and I am interested in how the occupancy of the two main public floors changes at the same crowded time (4 pm) from Monday to Friday. The project focuses on public areas of the first and second floors and excludes private rooms. Observations were made at approximately 4 pm to ensure consistent collection from Monday to Friday.
- One observation represents one manual occupancy count of one floor. For each observation, I recorded the date, time, approximate occupancy count by my method, estimated noise level based on my hearing, and the optional notes when my counting accuracy was affected by high movement. Because this project was done by me alone, all observations were collected by me using the same general procedure.
- To make my counting process more manageable, I divide each floor into sections, count the occupants in each section, and calculate the sum to estimate the total occupancy of each floor. Each occupant was counted as 1, and a fully occupied four-seat table was counted as 4 to simplify the count.
- The collection provides the variation across location (first and second floor), date, and observations collected from Mondays to Fridays. I know the design has many limitations: the private room is inaccessible, and observations were made only at approximately 4 pm because that is the only time I don't have any classes throughout the week. Therefore, the data doesn't represent library occupancy for the entire day. My manual counting process may also miss or double-count occupants who enter, leave, or move between sections. In addition, the noise level measurement is based on my personal feeling rather than an objective sound measurement.

 
## Initial Question
1. Which floor has greater occupancy at 4 pm (first or second)? 
2. What is the change in the occupancy rate of the first and second floors throughout the week?
3. What is the relation between the noise level correlated with the floor and occupancy? 
4. Is there any specific day when occupancy is either abnormally low or high?


| Attribute | Type | Description | Example |
|---|---|---|---|
|date|Temporal|Date of observation|9/21/2026|
|time|Temporal|Time of observation|4 pm|
|floor|Categorical|Observed library floor|first|
|occupancy_count|Quantitative|Approximate number of occupancy|53|
|noise_level|Ordinal|Overall perceived noise level of the floor|Quiet|
|notes|Text|Optional notes|High movement|


## Task 2: Pilot and Data Collection

### Pilot collection
- From Monday 9/21 to Friday 9/25, each day I collected 2 pilot observations of the first and second floors. In each observation, I counted the total number of occupants in the floor's public area. To make this task easier, I counted the number of fully table and the number of individuals, then calculated the total occupants using the formula: individuals + fully table * 4. Because some people could move while I was counting, the occupancy result should be treated as approximate only. 

### Pilot reflection and revisions
- The pilot showed that the first floor was easy to count because of its small area, while the second floor was more complicated than I expected because the public area is much larger and more crowded. Sometimes the noise distracted me when I was counting. 
- To improve the consistency, I divided the second floor into small sections and applied this method to all the second floor's observations. This made the process more manageable, even though I knew that an error could occur because some occupants were moving between sections. 
- The noise_level attribute was difficult to estimate consistently, although I estimated it by Decibel X, the number of each measurement attempt was heavily affected by the crowd. To make it more systematic, I defined 3 ordered levels: Quiet, Moderate, Noisy.


## Task 3: Data description and Domain questions

### Dataset description
- The final library dataset is based on 10 observations from 9/21 to 9/25 on the public section of the UIC Richard J. Daley Library’s first and second floors around 4 pm. This dataset contains the date, time, floor, estimated number of occupants, noise level, and notes.
- All information is recorded at 4 pm each collection and does not include other times or other areas. Manual counting may miss or double-count people who do not stay in one position during the observation. 

### Reflection on the Data
- The data that is collected contains no more information than when and where an observation takes place, how many people were there, and at what noise level the floor was. However, it says nothing about who these people are (students, TAs, professors, or staff), what they do there, or how long they stay.

### Final domain questions
1. What is the occupancy disparity on each day between the first and second floors? 
2. Is there a correlation in terms of the occupancy levels on the first floor and second floor for 5 days?
3. Is there a relation between the perceived noise levels and occupancy levels for each floor?
4. On which days are the highest and lowest occupancies recorded?

## Task 4: Task abstractions
| Domain question | Task Abstraction |
|---|---|
| **1** | **Action:** Compare occupancy values between the first and second floors.<br>**Target:** `occupancy_count` by `floor` and `date`.<br>**Abstract task:** Compare quantitative values across categories and dates. |
| **2** | **Action:** Compare occupancy patterns across five days.<br>**Target:** `occupancy_count` over `date`, grouped by `floor`.<br>**Abstract task:** Compare temporal patterns across categories. |
| **3** | **Action:** Examine the relationship between occupancy and noise level.<br>**Target:** `occupancy_count` and `noise_level`, grouped by `floor`.<br>**Abstract task:** Examine the relationship between a quantitative and an ordinal attribute. |
| **4** | **Action:** Find the highest and lowest occupancy values.<br>**Target:** `occupancy_count` by `date`.<br>**Abstract task:** Find extrema across temporal categories. |

## Task 5: Visualization Sketches

### Sketch 01
![Sketch 01](sketches\sketch01.png)
This sketch compares occupancy between the first and second floors across the five collection days. Three attributes used are date, floor, and occupancy_count. Marks are bars, height representing occupancy, and horizontal position representing date and floor. This design makes it easy to compare the two floors but hard to show patterns across the five days.

## Task 6: Summarizing 

## Task 7: Collaboration Process

