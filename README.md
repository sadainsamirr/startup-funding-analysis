# Startup Funding Analysis

This project analyzes startup funding data from a CSV file to extract insights such as trends in investments, popular startup locations, funding distribution by city, investment types, industries, and top investors.

## Trend of Investments Over the Years

The script `investment_trend.py` analyzes the trend of investments over the years. It calculates the total number of fundings done each year, plots a line graph showing the trend, and prints the year-wise total number of fundings in ascending order.

## Cities Chosen for Starting a Startup

The script `startup_cities.py` identifies the top 10 Indian cities with the most number of startups. It cleans the city names, counts the startups in each city, and visualizes the data with a pie chart. Additionally, it prints the city names and the number of startups in each city.

## Funding Received by Cities

The script `city_funding.py` finds the top 10 Indian cities with the most amount of funding received. It calculates the percentage of funding each city has received among the top 10 Indian cities and prints the city and percentage with two decimal places after rounding off.

## Distribution of Funding by Investment Type

The script `investment_distribution.py` analyzes the distribution of funding by investment type. It identifies the percentage of amount funded for each investment type and visualizes the data with a pie chart. Additionally, it prints the investment type and percentage of amount funded with two decimal places after rounding off.

## Companies Getting Easily Funded

The script `company_funding.py` determines the top 5 industries and the percentage of the total amount funded to each industry. It cleans the industry names, calculates the percentage of funding for each industry, and visualizes the data with a pie chart. Additionally, it prints the industry name and percentage of the amount funded with two decimal places after rounding off.

## Top Investors

The script `top_investors.py` identifies the investors who have invested the maximum number of times. It counts the number of times each investor has invested and prints the investor name along with the number of times invested as an integer value.

## Dataset

The dataset used for analysis is the 'startup_funding.csv' file.

