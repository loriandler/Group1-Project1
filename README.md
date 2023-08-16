# Group1-Project1

## Group 1 Members
 - Arnold Miranda Reynoso
 - Clover Mclaughlin
 - Jacob Anderson
 - Logan Severson
 - Lori Andler

### Project Slides: 
https://docs.google.com/presentation/d/1Q9t6MkW9AO1p_oKjZwu-jBw764srbWAwcXw6WTie7Y0/edit?usp=sharing 

 ## Project Title
 ### Completion rate between 4-year private and public universities across the state of Minnesota

## Project Description
At the start of our project, we began by comparing the undergraduate graduation (completion) rate of Private and Public colleges and universities St. Paul, Minnesota.  During the data cleaning process,  we found the data set started with 11 schools.  Initially we had 16 schools in our data pool of schools in St. Paul, Minnesota.

We called all of the variables and put them in a school summary data frame.
We excluded the 2-year schools, excluded the Luther Seminary and William Mitchell School of Law
Bringing the data to a total of 8 schools:
1.    Bethel University
2.    Concordia University – St. Paul
3.    Hamline University
4.    Macalester University
5.    Metropolitan State University
6.    University of Northwestern-St. Paul
7.    University of St. Thomas
8.    St. Catherine University

Then we re-ran all of the data to include both Minneapolis and Saint Paul as we weren’t getting a large enough public university pool.  In order to do a better analysis on the date, the data pool was still not big enough.  

We pivoted the project and pull 4-year private and public universities across the state of Minnesota.   The data was then run through a worldwide city to get us a total of 19 4-year private and public universities from across the state of Minnesota. 

Our project data now includes:
1. Bemidji State University
2. University of Minnesota-Crookston
3. University of Minnesota-Duluth
4. The College of Saint Scholastica
5. Minnesota State University-Mankato
6. Augsburg University
7. University of Minnesota-Twin Cities
8. Minneapolis College of Art and Design
9. Concordia College at Moorhead
10. Minnesota State University-Moorhead
11. University of Minnesota-Morris
12. St. Olaf College
13. Saint Cloud State University
14. Hamline University
15. Macalester College
16. University of St. Thomas
17. St. Catherine University
18. Gustavus Adolphus College
19. Winona State University

## Overview insight:
1. Each School Summary
     - Total number of students
     - What is the percentage of graduation rate?
     - Retention Rate
     - Diversity breakdown - graduation rate across different ethnicities
2. Public vs. Private Summary
     - Total number of students
     - What is the percentage of graduation rate?
     - Retention Rate
     - Diversity breakdown - graduation rate across different ethnicities

 ## Research Questions:
 ### Public Vs. Private
1. The correlation between % of ethnicity vs. completion rate
     - We found that the completion rate at private colleges of caucasian students was highest followed by completion rates of hispanic, asian, and two or more races.
     - Completion rate at Macalester College was the highest and Augsburg/St. Catherine were the lowest at the private colleges.
     - The box plot created shows that at private colleges the greatest span of completion rates was with the American Indian/Alaska Native ethnicity.
     - The pie chart shows that there aren't a huge amount of difference in the ethncity with completion rates at the private universities/colleges.
2. The correlation between total students and completion rate
     - The overall completion rates show that private colleges have the highest completion with an outlier of the University of MN for public colleges.
3. The correlation between retention rate(completing at least 1 year) and completion rate.
     - The retention rates are fairly in line with the completion rates between all of the schools public and private.
4. Comparing the completion rate between public and private schools
     - Overall, the private schools have a better completion rate than public schools.
     - The ttest shows the p-value is lower than the alpha and there is a statistical significance to the difference.

## Breakdown of Tasks
 - Data Cleansing & Analysis : Arnold, Clover, Jacob, Logan and Lori
 - ReadMe File Write-up: Lori
 - Visualization: Logan, Arnold, Jacob
 - Conclusion/professional write-up: Arnold
 - Finalized slide deck: Jacob

 We searched data sets for college stats on graduation rates, drop out rates, acceptance rates, tuition, etc.

 We used Python code in Jupyter Notebooks and Visual Studio Code to scrub the data and run the visualizations using the dependencies of: import json & import requests


 ## References
 Base URL: https://api/data.gov/ed/collegescorecard/v1/schools.json?
 Dataset Guide: https://github.com/RTICWDT/open-data-mater/blobl/master/API.md
 Guiding data: https://countrystatecity.in/docs/api/cities-by-state-country/

 ## Credits
 Thank you to instructor, Hunter Hollis, and TA's Randy & Sam for their guidance in this project.
