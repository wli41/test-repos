Query 1. 
This query show the relationship between the number of storm and average max and min temperature in each state, each year. This query joins the temperature table, location table in the main dataset and the storm_event, state tables of the secondary dataset. It calculate the number of storm event of each state and each year matches them to the annual average max and min temperature.

Query 2.
This query show the relationship between the number of storm and average precipitation in each state, each year. This query joins the precipitation table, location table in the main dataset and the storm_event, state tables of the secondary dataset. It calculate the number of storm event of each state and each year matches them to the annual average precipitation.


Query 3.
This query show the relationship between the number of storm and average wind speed in each state, each year. This query joins the windspeed table, location table in the main dataset and the storm_event, state tables of the secondary dataset. It calculate the number of storm event of each state and each year matches them to the annual average wind speed  in that state and year.

Query 4 
join the result of Query 2 to the result of Query 3 on where state in the result of Query 2 =  state in the result of Query 3, 
and where year in the result of Query 2 = year in the result of Query 3. The result should show the number of storm events in every states 
with average temperature, average precipitation, average wind speed in each year. Then we can compare the relationship between weather factors 
like average temperature, average precipitation, average wind speed, and the number of storm events.

Query 5
This query will join state attributes in main dataset (within maindataset, join on station_id) and second dataset to find states that have the greater number of storm events than average with the average of minimum temperautre, and the average of maximum temperature. To do this, we need to cleanse state values in dataset2 because the values are in full state name instead of abbreviations.

Query 6
This query will join state attributes in main dataset and second dataset to list states and storm names that have have the greater number of storm events than the average number of storm events in each year with 
average value of windspeed and precipitation in main dataset to see relationship between (windspeed and precipitation) and the type of storm name.
This query will group by states, storm names. 
