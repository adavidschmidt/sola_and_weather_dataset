# sola_and_weather
Create a dataset for future analysis and modeling to predict solar energy output.

This is a personal project. The goals of the project were to create and clean a dataset that I can use for future analysis and review of my solar production.

Data sources:
Weather data was sourced from the National Center for Environmental Information (NCEI) (https://www.ncei.noaa.gov/cdo-web/datatools/lcd) with my location.
Solar data was sourced through my solar micro-inverter provider (Enphase Energy)

Key features of the project:
1. Using Pandas library
2. Confirming the datatypes of the dataset's columns
3. Cleaning and transforming the data
4. Joining datasets
5. Creating a final dataset with only columns needed for analysis


Documents in the repository:

Solar_dataset.ipynb - This is the notebook containing the code used to create the solar_and_weather.csv dataset

solar_data.csv - This is the solar data generated and sourced from the micro-inverter provider.

weather_subset.csv - This is part of the weather data generated and sourced from the NCEI. The original dataset is too large to include in this repository. Sampling steps can be seen in the notebook.

daily_solar_weather_data.csv - This is the dataset containing the weather information as well as the solar information for the whole day. This will be used for future analysis and predictive modeling.

hourly_solar_weather_data.csv - This is a dataset containing hourly information on weather and solar data. This dataset is missing some information due to datetime differences in the weather and solar datasets; however, will still be useful for generating models and analysis on hourly changes.
