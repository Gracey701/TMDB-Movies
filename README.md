# TMDB Movies Data Exploration
### Author: Grace Seo
## Purpose
Analyzed data to see correlations between revenue and multiple features such as certification, movie duration, and average rating. 
## Methods
- Simple filtering and cleaning of data prior to data exploration
- Additional movie data from TMDB (https://www.themoviedb.org/) were added to the already existing data for further analysis
- With all the data, they were imported into an SQL database for facilitated access
- Based on questions needed to be answered, null and alternative hypotheses were constructed for each 3 questions which were then either rejected or failed to be rejected
  - Q1: Revenue vs Certification
  - Q2: Revenue vs Movie Duration
  - Q3: Revenue vs Average Rating
- Detailed filtering depending on what exact info is needed for the questions
- Depending on the type of target and variable, the type of test was determined to run for each question
- After all assumptions were cleared tests were ran and the null hypotheses were either rejected or failed to be rejected
  - Q1: Reject the null (There is a correlation between revenue and certification)
  - Q2: Reject the null (There is a correlation between revenue and movie duration)
  - Q3: Reject the null (There is a correlation between revenue and average rating)
## Results 
### Figure 1
![image](https://user-images.githubusercontent.com/113087687/213648224-d2dbaff6-48bc-4307-bb8d-a01972091437.png)
Very concentrated revenues around 0, can tell PG and PG-13 certified movies get higher revenues on average.
### Figure 2
![image](https://user-images.githubusercontent.com/113087687/213651258-0138d52d-4117-457c-9853-d47fe9868698.png)
As shown in the legend, movies that run for longer seem to earn a bigger revenue.
### Figure 3
![image](https://user-images.githubusercontent.com/113087687/213652133-18478378-572b-4d54-8d7b-b3b7d01829a8.png)
Looking at the legend, movies that get higher ratings also earn much higher revenues.
## Conclusions
Based off of the 3 answered questions, it is safe to assume the movies with higher ratings and longer runtimes earn much more revenue. As for the certification, those that have a PG and PG-13 age rating seem to earn more revenue.
# Source of Data
Data was retrieved from "https://www.themoviedb.org/"
