# CS 424 Assignment 1

## Task 1: Observation and Data Collection
- Topic: Richard J. Daley Library occupancy
- Location: 1st and 2nd Floor, excluding private area
- Observation time: Around 4 pm every day
- Count: One manual count of one floor
- Collection method: Divide each floor into sections, count - by section, and add them together

## Initial Question
1. How does occupancy differ between Floor 1 and Floor 2 at around 4 PM?
2. Is the difference between Floor 1 and Floor 2 occupancy stable across days?
3. How does occupancy change across different days?
4. Are there particular days with exceptionally high or low occupancy?

| Attribute | Type | Description | Example |
|---|---|---|---|
|date|Temporal|Date of observation|9/21/2026|
|time|Temporal|Time of observation|4PM|
|floor|Categorical|Observed library floor|1st|
|occupancy_count|Quantitative|Approximate number of occupancy|53|
|noise_level|Ordinal|Overall perceived noise level: Quiet/Moderate/Noisy|Quiet|
|notes|Text|Unusual condition during the observation|High movement|


## Task 2: Pilot and Data Collection

### Pilot collection
- I have collected 10 pilot observations across five days (9/21-9/25).
- Each day, I observed the public area of both Floor 1 and Floor 2 at approximately 4 pm
- Occupancy was counted manually by dividing the floor into sections and adding them together. 
- I counted 1 for each occupant and 4 for each fully table.
- The counts are approximate because occupants may enter, leave, or move between sections during my counting process.

### Pilot reflection and revisions
- Counting floor 1 was easy, but floor 2 was more difficult than I expected because the number of occupants was much higher, and some people kept moving during my counting process.
- Therefore, I divided the floor into sections, which made the counting process easier, manageable, and consistent. However, the occupancy counts should be treated as approximate rather than exact, since some people are moving.
- The noise_level attribute was hard to estimate, so I defined 3 ordered levels: Quiet, Moderate, Noisy, to make it more systematic. 

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

