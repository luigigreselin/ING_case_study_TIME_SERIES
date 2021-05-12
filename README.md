# ING_case_study
Predict the sales of 1881 liquor shops in a undefined country

# Overview

The case study is about predicting the future sales of a number of different liquor shops in un undefined area. Sales of the previous 5 years (from 2012 to 2017) are given
weekly for 7 different drink categories. A second dataset reports which shops are present in a radius of 5 km for each single shop to take into account the competition between different shops. 

# Data preprocessing / EDA
1. elimation of the nan
2. elimantion of all those shops that did not have data for the 2017 (they closed/failed)
3. elimination of those shops that have less than 52 rows reported (one year of sales) as they necessitate of different funding, compared to well structured and on going activities
4. summing up of the 7 categories to obtain the total sales
5. In the second dataset, elimination of all those shops that did not have any record in 2017 and were younger than 52 weeks

# Model & Statistical Analysis
I used the [Prophet model](https://facebook.github.io/prophet/) released by Fb to predict the total sales. I extracted the yearly trend, for the predicted performance in 2018, and then I classified them with an ANOVA, to check for differences between three homogenehous groups, being no competitors, few competitors and more then 6 competitors. No significant difference was found.

# Data
can be found in the attached files
