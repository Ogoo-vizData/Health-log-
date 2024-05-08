# HEALTH LOG INSIGHTS
### Exploratory analysis conducted on a health dataset using SQL, DAX queries, and Power BI as a visualization tool.

## Project Overview
This project is based on a dataset from Kaggle about heart conditions, blood pressure (BP), heart rate, and sugar levels among different genders in various age groups. The analysis utilized various tools at an expert level to develop insights and better understand the data for enhanced understanding of average health conditions across different age groups.

## Tools
- SQL - Data cleaning and analysis.
- Power BI - Data transformation and visualization.


## Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
- Data loading and inspection.
- Data cleaning and formatting.
- Created two new columns to group the age in decades and another new measure for 5-year bins in Power BI.

## Exploratory Analysis
- I altered the data type of different columns using ALTER TABLE [dbo].[heart_statlog] ALTER COLUMN sex VARCHAR(10);, replacing the column name with the respective column names.
- The dataset was moved to Power BI for further data transformation and visualization.
- Using charts and graphs, various insights were visualized, such as the respective BP, blood sugar, and exercise-induced angina when influenced by age bracket, sex, and     previous heart conditions.

## Observations
- The average cholesterol level is 210.36 mg/dL.
- The average resting blood pressure is 132.15 mmHg.
- The maximum heart rate is 139.73 bpm.
- Females tend to have higher cholesterol levels.
- The age group of 50-60 shows more severe heart conditions and higher cholesterol levels.
