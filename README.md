# CS 424 Assignment 1

## Task 1: Observation and Data Collection
Topic: Richard J. Daley Library occupancy
Location: 1st and 2nd Floor, excluding private area
Observation time: Around 4pm every day
Count: One manual count of one floor
Collection method: Divide each floor into section, count by section and add them together

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
I have collected 10 pilot observations across five days (9/21-9/25).
Each day, I observed the public area of both Floor 1 and Floor 2 at approximately 4PM
Occupancy was counted manually by dividing floor into sections and add them together. 
I add 1 for each occupants and 4 for each fully table.
The counts are approximately because occupant may enter, leave or move between section during my counting process.

### Pilot reflection and revisions
Counting floor 1 was easy, but floor 2 was more difficult than I expected because the number of occupancy was much higher and some people keep moving during my counting process.
Therefore, I divide the floor into sections, which made the counting process easier, manageable and consistent. 
However, the occupancy counts should be treated as approximately instead of exactly because some people moving.
The noise_level attribute was hard to estimate, so I defined 3 ordered level: Quiet, Moderate, Noisy to make it more systematic. 

## Task 3: Data description and Domain questions

## Task 4: Task abstractions

## Task 5: Visualization Sketches

## Task 6: Summarizing 

## Task 7: Collaboration Process

