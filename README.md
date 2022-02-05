# Crops-and-Livestock-Products-in-Europe

This research aims to analyse how crops and livestock data for Europe over the past 20 years has changed.

The [data](https://www.fao.org/faostat/en/#data) for this research was taken from the the Food and Agriculture Organisation of the United Nations, which maintains records of crop and livestock products for all countries and regions around the world. For crops, statistics are regularly recorded for 173 products and data regarding harvested area, yield and production quantity is covered. 

The first part of the research deals with investigating how changes in area usage for harvestation has been impacted over the time period for each European country, where area usage is calculated as a percentage of the overall area. The area data is taken from [this GitHub repository](https://raw.githubusercontent.com/ajturner/acetate/master/places/Countries-Europe.csv). The second part of the research analyses the production quantities of the top five produced items, through which a prediction for the following two years is made for each item. The method used to implement a prediction is linear regression. This method was chosen due to the data for each item generally following a linear trend.

To achieve the results, various Python libraries for data analysis were used, including 'pandas' for data cleaning, 'matplotlib' for creating plots of the data, and 'scikit-learn' for linear regression. 

