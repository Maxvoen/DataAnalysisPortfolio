# 2015 Nigeria Presidential Elections Analysis

## Project Overview

This data analysis project aims to provide insights into the voting pattern across the country. By analyzing various aspects of the elections data, we seek to ascertain the level
of voter apathy, make data-driven recommendations, and gain a deeper understanding of states, regional, geopolitical zone, and political parties performance.

<img width="589" height="332" alt="2015 Pres Screenshot" src="https://github.com/user-attachments/assets/e140253c-6281-484e-9027-50c892bbf16d" />


### Data Sources

Elections Data:
 - [Downlaod here](https://docs.google.com/spreadsheets/d/1sIBNUpCJbC_x7UGm8VV6IuSCKl2m9PeP/edit?usp=drive_link&ouid=113380697195263828971&rtpof=true&sd=true)

## Tools

- Power Query - Data Cleaning/transformation
- Power BI - Creating reports

  ### Data Cleaning/Preparation
  In the initial data preparation phase, we performed the following tasks:
  1. Data loading and inspection.
  2. Data duplication and unpivoting
  3. Data modelling
 
  ### Exploratory Data Analysis

  - What is total number of registered voters?
  - What is the total votes cast?
  - What is number of participating political parties?
  - How many states participated?
  - With what number of votes was the elections won?
 
  ## Data Analysis

  ``` dax
  SUM('Election Data'[regvoters])
  ```
  

