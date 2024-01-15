# XYZ SUPERMARKET DATA ANALYSIS
Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.

# Project Steps
imported the neccesary libraries os, glob, pandas, matplotlib, seaborn, and catplot
used glob to match 'csv' files in the directory and combined different branches into one dataframe using concat method of pandas
got basic information of the combined data using pandas head() and info() methods
got the summary statistics using the pandas desscribe method and checked for missing values using isnull().sum() method
extracted features from date column; converted the data into datetime and created new columns for month, day and hour
got the unique sales hours using unique() method
used groupby() method to generate insights from the data
used matplotlib, catplot and seaborn for visualization

# Insights
There was an average rating of 6.9727, The lowest was 4
Porthacourt branch had the highest sales with abuja branch having the lowest
Porhacourt had the highest gross income and highest cost of goods sold
Lagos had the most customers followed by abuja then porthacourt
Epay and cash were the most used payment methods
Fashion accesories made the most sales while Health and beauty made the least sales
Abuja branch had the best customer rating
Electronic accessories sold the most quantity
More sales was made from females than males
7pm was the time of the day with the most sales with sports and travel products sold the most at this time
15th was the day of the month with the most sales


# Future Work
Build predictive models, such as regression or time series forecasting models, to predict future sales based on historical data.
Use machine learning for customer segmentation and personalized marketing strategies.
Explore opportunities to integrate external data sources for a more comprehensive analysis, such as economic indicators, weather data, or social media trends.
Build machine learning models for product recommendation system
Set up automated processes to update the dataset regularly, ensuring that the analysis is based on the most recent data.
Create interactive dashboards using tools like Tableau or Plotly to allow users to explore and analyze the data dynamically.

# Standout Section
Did daily, monthly and hourly sales trends
Got the time of the day and day of the month with the highest sales
got the most sales made based on gender
got the customer with the highest purchase



