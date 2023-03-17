# World Happiness EDA

** Summary:

The World Happiness EDA (Exploratory Data Analysis) is a project that explores the happiness levels of countries around the world. It involves analyzing a dataset containing information on various factors that contribute to happiness, such as GDP, social support, and life expectancy, and examining how these factors are related to the overall happiness levels of countries.

The project begins by importing and cleaning the dataset, which includes data from the World Happiness Report for multiple years. The data is then explored through visualizations and statistical analysis, including correlation matrices and regression models, to identify trends and relationships between the different variables.

Some of the key findings of the analysis may include identifying which factors have the strongest correlation with happiness levels, how different regions of the world compare in terms of happiness, and which countries have experienced the most significant changes in happiness levels over time.

Overall, the World Happiness EDA project aims to provide insights into the factors that contribute to happiness and how these factors vary across different countries and regions. The results of the analysis may be useful for policymakers and individuals seeking to improve the happiness and well-being of populations.

You can find the dataset:  https://www.kaggle.com/datasets/unsdsn/world-happiness.


** Contents:

1. Introduction: using OOP to introduce myself
2. Exploring World Happiness Report 2015.
3. Exploring the Categorical Variables vs. Happiness Score.
4. Exploring the Numerical Variables: how the Social Factors contribute to The Happiness in the World.
5. Comparing the World Happiness 2015-2019 reports by:

        a. Preparing the data to merge all the reports together.
        b. Adding the Region column to 2017,2018,2019 reports.
        c. Dealing with the null values after adding the Region coulmn.
        d. Joining all the reports together and Exploring the new data.
        
      
** Findings:

    *** Country level visualizations :


    1. Finland is the country with the highest Happiness Score in the years 2015-2019.
    2. UAE is the country with the strongest Economy in the years 2015-2019.
    3. Iceland is the country with highest social support(family) in the years 2015-2019.
    4. Singapore is the country with best health in the years 2015-2019.
    5. Uzbekistan is the country with the highest freedom in the years 2015-2019.
    6. Myanmar is the country with the highest Generosity in the years 2015-2019.
    7. Rawanda is the country with the highest Trust in the years 2015-2019.

    On the other hand:

    1. Togo is the country with the lowest Happiness Score in the years 2015-2019.
    2. Somalia is the country with the lowest Economy in the years 2015-2019.
    3. Central African Republic  is the country with lowest social support(family) in the years 2015-2019 = zero.
    4. Sierra Leone  is the country with worst health in the years 2015-2019.
    5. Iraq and Afghanistan are  the countries with the lowest freedom in the years 2015-2019.
    6. Greece is the country with the lowest Generosity in the years 2015-2019.
    7. Moldova  is the country with the lowest Trust in the years 2015-2019.

    *** Region level visualizations:

    1. Western Europe is the region with the highest Happiness Score in the years 2015-2019.
    2. Middle East and Northern Africa is the region with the strongest Economy in the years 2015-2019.
    3. Western Europeis the region with highest social support(family) in the years 2015-2019.
    4. Southeastern Asia is the region with best health in the years 2015-2019.
    5. Central and Eastern Europe  is the region with the highest freedom in the years 2015-2019.
    6. Southeastern Asia is the region with the highest Generosity in the years 2015-2019.
    7. Sub-Saharan Africa is the region with the highest Trust in the years 2015-2019.

    On the other hand:

    1. Sub-Saharan Africa is the region with the lowest Happiness Score in the years 2015-2019.
    2. Sub-Saharan Africa is the region with the worst Economy in the years 2015-2019.
    3. Southern Asia the region with lowest social support(family) in the years 2015-2019.
    4. Sub-Saharan Africa is the region with worst health in the years 2015-2019.
    5. Southern Asia   is the region with the lowest freedom in the years 2015-2019.
    6. Western Europe is the region with the lowest Generosity in the years 2015-2019.
    7. Central and Eastern  Europe is the region with the lowest Trust in the years 2015-2019.


** Conclusion:

According to this analysis,we explored 164 countries in 10 regions.
we can see that Family, followed by Economy and Health have the maximum effect in determining the happiness of people in a country.
The happiest country is FInland, the least happy country is Togo.
We can see that the happiest countries in the years between 2015-2019 lie in Westren Europe and the least happy countries in the same period lie in Sub-Saharan Africa. 
The mean of happiness score in the years between 2015-2019, almost did not change, the highest in 2019= 5.447595, Does that mean that we were happier in 2019 than in 2015!


