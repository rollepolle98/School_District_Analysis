# School_District_Analysis
Module 4: PyCitySchools with Pandas

# Overview of School District Analysis

## Purpose of Aynchronous Analysis
The purpose of the Ansychronous analysis is to help Maria whose job is to analyze standarized tests and student findings. We do this by first cleaning the data provided, merging data frames and caluclating key metrics. Once key metrics have been established, further analysis is done by altering key dependent variables in order to reveal trends of math, reading, and average scores for all schools in the district.

## Asynchronous Analysis Overview
The first task that we recieved in this analysis was to aggregate data and show trends in the data that was provided to us by Maria. Maria believes that a particular data set may be missing data so we are first tasked with inspecting if there is any missing data, which there is not. The next task is to get key metrics such as total number of students/schools, total budget, subject scores, subject pass percentages, etc. Using these key metrics, we are then tasked with generating a school district summary based on the several key metrics that we previously calculated. Using the school district summary we are then able to go more in depth and analyze the trends of average reading and math scores by changing the dependent such as schools size, amount spent per student, and school types.

## Purpose of Challenge Analysis
In the challenge analysis we are tasked to further analyze the the school district analysis, reason being is that Maria believe that the students_complete.csv shows evidence of academic dishonesty specifically for reading and math grades of ninth graders at Thomas High School. Maria would like help re analyzing the school district analysis but this time around without the scores of ninth graders from Thomas High School. After this analysis is done she would like to have a report showing how this affected the total analysis. 

## Challenge Analysis Overview

First we are tasked with replacing the reading and math scores of the ninth graders at Thomas High School with `NaN` using the `loc` method with conditional statements and logical operators. Next, Using the same anaylsis completed in the asynchronous material we will then analyze the trends again but this time without data for ninth graders at Thomas High school.


# Analysis of School District Analysis
 
Now that we have completed the analysis with and without ninth graders from Thomas High School we can clearly see how the data was affected. 

- The district summary was slightly affected in that passing math % decreased by .6% (75% to 74.4%), passing reading % decreased by .8% (86% to 85.2%), and overal passing % decreased by .6% (65% to 64.4%)

- The school summary was only affected for Thomas High School but not any of the others due to the fact that only scores for ninth graders at Thomas High School were altered but not for any other school.

- Replacing the math and reading scores for ninth graders at Thomas Highschool did not affect the total number of students, total school budget or per student budget. While it did slightly affect all the average scores and pass percentages. Relative to other schools it made a significant difference due to the fact that prior to expenting the scores, Thomas High School was in the top 5 and after it was not. 

