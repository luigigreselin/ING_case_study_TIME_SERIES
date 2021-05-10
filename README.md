# ING_case_study
Predict the sales of a liquor shops in a undefined country

The case study is about predicting the future sales of a number of different liquor shops in un undefined area. Sales of the previous 5 years (from 2012 to 2017) are given
weekly for 7 different drink categories. A second dataset reports which shops are present in a radius of 5 km for each single shop
to take into account competition between different shops. 

I used the prophet model released by Fb to predict the total sales, and then I runned an Anova to check for differences between three homogenehous groups, being no competitors, 
few competitors and more then 6 competitors. No significant difference was found.
