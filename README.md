# KTX Growth

## Purpose
To show my ability to cleanse, analyze, and present data. 

## Process
After examining the raw data, I used SQL to join 2 of the 3 datasets, and export it as a CSV file.
![SQL](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/SQL%20Query.png)


I then loaded the remaining file and the new one into Jupyter Notebook, and merged them together to create one dataframe.
![merge](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/merged.png)

I cleaned up the data (examples: deleted a repeated student ID number in the "enrollment" set, deleted the periods to have blank cells, made sure all said "Reading" instead of "Read", etc.), and then decided to drop the "year" column as it wasn't useful to my analysis because the entire dataset was from the year 2019.
![year](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/drop%20year.png)


I also filtered the original dataframe, making 6 others that were much more specific.  I did not end up needing these, but I like having more specific data ready in case it is needed. I made new DataFrames for Overall Math Scores, Overall Reading Scores, Fall Math Scores, Spring Math Scores, Fall Reading Scores, and Spring Reading Scores.
![new](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/new%20dataframes.png)


I exported my unfiltered dataframe as a CSV file, and used this to do visualizations in Tableau.
![csv](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/to%20csv.png)


## Results
- I learned that student scores at each school are consistent between math and reading.
![avg_yearlong](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/Average%20Year-Long%20Overall%20Scores.png)

- When we break the scores down between Fall and Spring terms, we can see that scores went up in every area, at every school.
Note: School G (grades 0 - 2) has the lowest scores of all the schools, but also saw the highest level of growth.
![detailed_comparison](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/Detailed%20Scores%20Comparison.png)

- Schools A, B, C, & D: Grades 5-8
School E: Grades 0 - 4
School F: Grades 0 - 3
School G: Grades 0 - 2
We see double the growth in younger grades than we do in the older ones.
![overall_growth](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/Overall%20Growth.png)

- The typical growth between Fall and Spring is halved after 1st grade, then almost halved again after 5th grade, with a steady decline in between.
![growth_by_grade](https://github.com/charlagarcia/KTX_Performance_Task/blob/main/resources/Growth%20by%20Grade.png)

[Link to Tableau story](https://public.tableau.com/app/profile/charla.garcia/viz/KTX_Growth/KTXGrowth?publish=yes)
