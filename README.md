## USA Accidents(7.7 million records) EDA Python Project
- This dataset collected from Kaggle.
- Dataset Name: USA Car Accident Dataset (2016-2023)
- Coverage: 49 states in the USA
- Time Period: February 2016 to March 2023
- Accident Records: Approximately 7.7 million accident records
- Data Sources:
  US and state departments of transportation,
  Law enforcement agencies,
  Traffic cameras,
  Traffic sensors within road networks.
- Purpose: Provides insights into accident patterns, causes, and trends across
  the country
- Potential Use: Analysis of traffic safety, accident prevention, and  
  mitigation strategies

## Dataset Used
- <a href = "https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents">Dataset</a> 

## Basic questions
1. Are there more accidents in warmer or colder areas?
2. Which 5 states have the highest number of accidents? How about per capita?
3. Among the top 100 cities in number of accidents, which states do they belong to most frequently.
5. What time of the day are accidents most frequent in?
6. Which days of the week have the most accidents?
7. Which months have the most accidents?
8. What is the trend of accidents year over year (decreasing/increasing?)
Process
Verify data for any missing values and anomalies, and sort out the same.
Made sure data is consistent and clean with respect to data type, data format and values used.
Created pivot tables according to the questions asked.
Merge all pivot tables into one dashboard and apply slicer to make dynamic.
## Insights from the Dataset:
#### Total Cities and Accidents:

- The dataset covers 13,679 unique cities across 49 states in the U.S.
- 8.9% of cities (1,218 cities) have more than 1,000 accidents yearly.
- 91% of cities have fewer than 1,000 accidents yearly.
#### Missing Data:

- Data for 2016 & 2023 is missing in large quantities.
#### High Accident-Prone Cities:

- New York: The most populated city, with 21,699 accidents over the years.
- Miami: The city with the highest number of road accidents in the U.S. (2016-2023).
- Houston: The second-highest number of road accidents in the U.S. (2016-2023).
- 10 cities out of 13,679 contribute to 15.8% of all accident records.
#### Top States for Accidents:

- California: The state with 1,741,433 accidents in the past 8 years, accounting for about 22% of the total accidents in the U.S.
- Florida: The second-highest state with 11.39% of total road accidents.
#### Lowest Accident City:

- South Dakota: The city with the lowest number of road accidents in the past 8 years, with only 289 accidents.
#### Year-over-Year Trends:

-Road accidents have been increasing year-over-year.
-2022 saw the highest spike in accident percentages over the last 8 years, with an increase of 22.8%.
#### Accidents by Day and Time:

- Sunday: The day with the lowest percentage of accidents.
- Weekdays: Road accidents are almost 2 times higher on working days compared to weekends. 15.93% of accidents occurred on weekends.
- Thursday: The day with the highest percentage of accidents at 17.68%.
- Peak Accident Hours:
6:00 AM to 8:00 AM: 20% of accidents occur during morning rush hours.
3:00 PM to 6:00 PM: 33% of accidents occur in the evening rush hours.
4:00 PM is the second most dangerous hour, aligning with office-returning times.
7:00 AM is the most dangerous hour, correlating with office-going hours.
#### Seasonal Trends:

- October to January: Almost 40% of accidents occur during the transition from autumn to winter months, indicating possible seasonal driving hazards.
#### Weather Conditions:

- 33.13% of accidents occurred in fair weather.
- 13% of accidents occurred in mostly cloudy conditions.
- Accidents are most common between 63°F (17.2°C) and 79°F (26.1°C) temperatures.
#### Accident Severity:

- Severity-4 (highly severe) accidents account for 2.65% of the total accidents.
- Severity-2 (moderately severe) accidents make up 80% of the total accidents.
#### Geographical Insights:

- After mapping with a sample dataset of size 0.0001, it becomes evident that most accidents occur in coastal areas, where larger populations reside, while middle America has relatively fewer accidents.
- These insights provide a comprehensive understanding of road accident patterns, including temporal, geographical, and severity trends, from the dataset of U.S. road accidents between 2016 and 2023.

## Summary and Conclusion
The dataset highlights the disproportionate number of accidents in high-population, coastal cities, as well as seasonal, time-of-day, and weather-related patterns. The increase in accident numbers year-over-year, especially in 2022, warrants focused efforts in urban planning, road safety measures, and policy changes in high-risk regions and during high-traffic times.

## Future Considerations:
Data Completeness & Consistency:

Fill missing data for 2016 & 2023 to ensure accurate trend analysis.
Ensure consistency in data formatting, including timestamps, coordinates, and weather conditions.
Integrate additional datasets (e.g., real-time traffic, road infrastructure, population density) to improve accident analysis.

Advanced Analytical Models:

Use machine learning to predict high-risk zones, times, and conditions for better safety and resource allocation.
Build models to predict accident severity based on weather, traffic conditions, and time, aiding emergency response.
