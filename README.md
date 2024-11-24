# (WIP) Community Safety Dashboard for Kensington and Chelsea
An interactive dashboard showing crime trends by type, time period, and location for community safety planning.
Because crime does not exist in isolation, I would like to compare this data with other data sources such as community investment and social services data, and other relevant data sources to provide a more comprehensive view of community safety. This data is currently limited to 2024 but I would like to expand this to include previous years to provide a more comprehensive view of trends.

Data source: UK Police Data API (https://data.police.uk/docs/)

This project includes:
- Interactive dashboard for exploring crime data by type, location, and time period 
- Map of crime locations for the most prevalent crime type

The dashboard is built using `matplotlib` and the map is made possible with `folium`. 

To run this project locally, you will need to install the required packages using the following command:
```
pip install -r requirements.txt
```

## Conclusions from the data: 

Violent and sexual offenses are the most prevalent type of crime in Kensington and Chelsea, with the highest number of incidents occurring in August.

There are a couple of notable geographical gaps in crime data (such as the area west of Holland Park), which may be due to underreporting or other factors. This is an area for further investigation.

## Next steps:

- Expand the data to include previous years to provide a more comprehensive view of trends
- Compare crime data with other data sources such as community investment and social services data
- Investigate geographical gaps in crime data to understand the underlying factors