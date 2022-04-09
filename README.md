# Unit-6---Pythonic-Monopoly-Final


Instructions

Rental Analysis
The first step to building the dashboard is to work out all of the calculations and visualizations in an analysis notebook. Once the code is running properly, it can be copied over to a dashboard code and used with Panel to create the final layout. Use the rental_analysis.ipynb to complete the following:

Dwelling Types Per Year
In this section, you will calculate the number of dwelling types per year and visualize the results as a bar chart using the Pandas plot function.
Note: By default, the colour of the bar charts is blue. However, it is hard to see the difference between the yearly data.
As an optional challenge, you can manually use the color parameter of the plot() function to change the colour of each bar chart.



Average Monthly Shelter Costs in Toronto Per Year
In this section, you want to visualize the average monthly shelter costs per year to understand rental income trends over time better. You will visualize the average (mean) shelter cost for owned and rented dwellings per year and visualize it as line charts.
As an optional challenge, you can plot each line chart in a different colour.


Calculate the average monthly shelter costs for owned and rented dwellings for each year.


Visualize the monthly shelter costs per year as line charts.



Average House Value per Year
In this section, you want to determine the average house value per year. An investor may want to better understand the sales price of the rental property over time. For example, a customer will want to know if they should expect an increase or decrease in the property value over time so they can determine how long to hold the rental property. You will visualize the average_house_value per year as a bar chart.


Calculate the mean average_house_value for each year.


Visualize the average_house_value per year as a line chart.

Average Prices By Neighbourhood
In this section, you want to compare the house value by neighbourhood.


Create a new DataFrame with the mean house values by neighbourhood per year.


Visualize the mean average_house_value per year with the neighbourhood as a dropdown selector.


Hint: Use hvplot to obtain the interactive dropdown selector for the neighbourhood.



Number of Dwelling Types per Year
In this section, you want to visualize the number of dwelling types per year in each neighbourhood. You want to provide investors a tool to understand the evolution of dwelling types over the years.
Hint: Use hvplot to create an interactive visualization of the average number of dwelling types per year with a dropdown selector for the neighbourhood.

Top 10 Most Expensive Neighbourhoods
In this section, you want to figure out which neighbourhoods are the most expensive. You will need to calculate the mean house value for each neighbourhood and then sort the values to obtain the top 10 most expensive neighbourhoods on average. Plot the results as a bar chart.


Neighbourhood Map
In this final section, you will read in neighbourhood location data and build an interactive map with the average prices per neighbourhood. Use a scatter Mapbox object from Plotly express to create the visualization. You will need your Mapbox API key for this.
Remember that to create maps visualizations using Plotly Express, you will need to create an account at mapbox and create an access token.


Dashboard
My dashboard contains bar charts, line charts, and map charts that all analyses the value of all home types across all neighbourhoods in the GTA. The Dashboard is user friendly as viewers can understand the data (presented visually) thoroughly. 
