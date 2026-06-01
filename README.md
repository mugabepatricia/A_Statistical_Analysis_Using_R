# Factors Influencing Academic Performance Among University Students: A Statistical Analysis Using R

## Project Overview

This project presents a complete end-to-end statistical analysis workflow conducted in R to investigate factors associated with academic performance among university students.

The study explores the relationship between student GPA and several potential predictors, including study hours, attendance rate, sleep duration, and gender. The project follows a research-oriented analytical process similar to that used in MSc dissertation projects.

The dataset used in this project was AI-generated and curated for educational purposes, providing realistic student performance data suitable for statistical analysis and methodological practice.

## Research Objective

To determine whether study hours, attendance rate, sleep duration, and gender significantly predict academic performance (GPA) among university students.

## Dataset Description

The dataset contains 120 student observations and the following variables:

- Variable - Description
- Student_ID - Unique student identifier
- Gender	- Student gender
- Department	- Academic department
- Study_Hours_Per_Day	- Average daily study hours
- Sleep_Hours_Per_Day	- Average daily sleep duration
- Attendance_Rate	- Class attendance percentage
- GPA	- Student Grade Point Average

## Tools and Technologies

* R
* RStudio
* tidyverse
* psych
* corrplot
* car
* ggplot2
* R Markdown

## Project Workflow

1. Data Import and Inspection

The dataset was imported into R and examined using:

* head()
* str()
* summary()

to understand data structure and variable types.

2. Data Cleaning

The data cleaning process included:

* Checking for missing values
* Identifying duplicate records
* Converting categorical variables to factors
* Verifying data integrity

Results:

* No missing values detected
* No duplicate observations detected
* Categorical variables successfully converted

3. Descriptive Statistics

Descriptive statistics were generated to summarize:

* Central tendency
* Variability
* Distribution characteristics

Metrics examined included:

* Mean
* Median
* Standard deviation
* Minimum and maximum values
* Skewness
* Kurtosis

4. Data Visualization

Several visualizations were created using ggplot2:

* Histograms
* Boxplots
* Scatterplots
* Bar charts

These visualizations provided insight into data distribution and variable relationships.

5. Correlation Analysis

Pearson correlation analysis was conducted to examine the relationship between Study Hours Per Day and GPA.

Results indicated:

* Moderate positive correlation
* r ≈ 0.616
* p < 0.001

This suggests that increased study time is associated with improved academic performance.

6. Simple Linear Regression

A simple linear regression model was fitted to predict GPA using Study Hours Per Day.

Key findings:

* Study hours significantly predicted GPA
* Positive regression coefficient
* Approximately 38% of GPA variation explained

7. Multiple Linear Regression

A multiple regression model was developed using:

* Study Hours Per Day
* Sleep Hours Per Day
* Attendance Rate
* Gender

Key findings:

* Study Hours Per Day was the strongest predictor
* Attendance Rate was statistically significant
* Sleep Hours Per Day was not statistically significant
* Gender was not statistically significant
* Model explained approximately 42.7% of GPA variation

8. Regression Diagnostics

Model assumptions were evaluated using:

* Residual plots
* Q-Q plots
* Variance Inflation Factor (VIF)

Results indicated:

* Residuals approximately normally distributed
* No serious multicollinearity issues
* Model assumptions reasonably satisfied

## Key Insights

Study Habits Matter

Study Hours Per Day emerged as the strongest predictor of academic performance.

Attendance Contributes to Success

Students with higher attendance rates tended to achieve higher GPAs.

Sleep Was Not a Significant Predictor

Although sleep is important for wellbeing, it did not significantly predict GPA after accounting for other variables in the model.

Gender Differences Were Minimal

Gender did not significantly influence academic performance within this dataset.

## Limitations

* Dataset was AI-generated for educational purposes.
* Additional factors influencing academic performance were not included.
* Cross-sectional data limits causal inference.
* Academic performance was measured solely using GPA.

## Future Improvements

Future analyses could incorporate:

* Socioeconomic factors
* Mental health indicators
* Prior academic achievement
* Learning styles
* Longitudinal data collection
* Machine learning approaches

## Learning Outcomes

Through this project, I strengthened my skills in:

* Data Cleaning
* Statistical Analysis
* Correlation Analysis
* Linear Regression
* Data Visualization
* Reproducible Research
* Academic Reporting
* R Programming

## Deliverables
- <a href="https://rpubs.com/Patricia_Mugabe/1437347">HTML Analysis Report</a>
- <a href="https://github.com/mugabepatricia/A_Statistical_Analysis_Using_R/blob/main/MSC%20Academic%20Performance%20Analysis.pdf">PDF Analysis Report</a>

## Author

Patricia Mugabe

Aspiring Data Analyst | Research Analyst | R Programming Enthusiast

Open to remote opportunities, research collaborations, and data analytics projects.

Connect with me on LinkedIn (https://www.linkedin.com/in/patricia-mugabe/) and explore more projects in my portfolio.
