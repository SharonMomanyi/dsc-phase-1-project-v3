AIRCRAFT ACCIDENTS ANALYSIS
Introduction
The company I work for is expanding into new industries to diversify its portfolio, and I am to determine which aircraft has the lowest risk, to help facilitate the start of this new business endeavor. We are specifically interested in purchasing and operating airplanes for commercial and private enterprises.

Objectives
Identify low-risk aircraft for the new aviation division.
Yield three business recommendations from the low-risk aircraft findings.
Business Problem
The questions I am seeking to understand are:

What trends and patterns are there in aircraft accidents to date?

Which aircraft makes(models) are most commonly involved in the accidents?

Does the weather condition play a significant role in causing aircraft accidents?

Which countries are associated with the highest count of aircraft accidents?

Data Understanding
I will be working with a dataset from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters. It is from Kaggle (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses).

My aim is to gain an understabding into the factors that cause accidents to be able to make recommendations on aircrafts associated with lowest risk.

The data is contained in Aviation_Data.csv and each record represents an accident incident, with details of its occurrence.


EXPLORATORY DATA ANALYSIS
I will now perform some Exploratory Data Aanalysis to be able to understand the data better and uncover patterns and relationships.

1. Accident trend over the years

![Accident trends](Images/Accidenttrends.png)

OBSERVATIONS.
The number of accidents is generally decreasing as the years go by.

The dataset seems to be missing information for the years 1962 to sometime in 1981.

1982 had the highest number of accidents.

2. Accident Counts by Aircraft Make
Here I am seeking to understand which aircraft Makes(models) are most commonly involved in the accidents.

![Number_of_accidents_by_make](Images/Number_of_accidents_by_make.png)

OBSERVATIONS
The Aircraft company involved with most accidents is Cessna. It has a significantlly higher number of accidents compared to the other aircraft Companies.
Grumman, Mooney, Robinson, Bellanca and Hughes have the lowest accident counts from our plot, but this is just a representation of the top 10 aircraft companies in terms of number of accidents.

3. Weather Conditions and Accidents
Let's now investigate if the weather condition plays a significant role in causing aircraft accidents.

![Accidents_by_Weather_Conditions](Images/Accidents_by_Weather_Conditions.png)

FINDINGS
From the above bar chart, most crashes happens in VMC, where weather is clear and pilot is flying by visual. This implys that weather is not a significant factor causing accidents.

4. Accidents by Country
Identify which countries have the highest number of aviation accidents.

![Accidents_by_Countries](Images/Accidents_by_Countries.png)

FINDINGS
The United States has significantly high number of accidents compared to the rest of the countries

OVERALL FINDINGS
The number of accidents is generally decreasing as the years go by.
The dataset seems to be missing information for the years 1962 to sometime in 1981.
The Aircraft company involved with most accidents is Cessna. It has a significantlly higher number of accidents compared to the other aircraft Companies.
Weather is not a significant factor causing accidents.
The United States has significantly high number of accidents compared to the rest of the countries
RECOMMENDATIONS
To be able to minimize risk in the new aviation division, i recommend;

Aircraft Particulars.
Purchasing aircrafts of Makes that are associated with a low accident count. The Cessna make should be avoided, together with the other makes that have high counts.
The high accident rates in the years in the 90's could be associated with old aircraft models. We should consider purchasing newer models and equiping them with enhanced autopilot systems that can assist pilots during high-risk situations.
Setting aside a budget for pilot training programs.
The finding that most accidents occur during clear weather suggests that accidents could be caused by human error.
Thorough training and awareness campaigns should be conducted for pilots to promote responsible flying and discourage risky behaviors. This will reinforce the importance of flying within established safety parameters which crucial in preventing accidents.
Areas of operations
We should consider beginning operations in countries associated with low accident counts. Areas like the US which has the highest accident counts should be ventured into at a later time when the department is well established.
