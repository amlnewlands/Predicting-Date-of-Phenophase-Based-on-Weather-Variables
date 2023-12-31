# Predicting Phenophase Presence Based on Weather Variables

This project was created for SIADS 696 Milestone 2 with a goal of demonstrating model-building and effective communication skills . It was built in collaboration with Linda Sylvester and Christian Ibanez Diaz.

Phenophases refer to the lifecycle events for plants such as first leaf, first bloom, bloom length, leaf fall, etc. Based on the findings of the Milestone I project, Impact of Climate Extremes on Vegetation, we were motivated to investigate using local weather variables (i.e. temperature, precipitation, solar radiation) to predict if given weather values are suitable for predicting a plant’s first leaf and first bloom. In order to summarize the weather leading up to the phenophase, we used a 30 day rolling average. We focused mainly on temperature as many research articles cite temperature as the main driver of the timing of phenological events. But we will also look at the additional weather variables, such as precipitation and solar radiation, in order to predict phenophases and categorize weather types.

The raw phenophase data used has been included as the file "individual_phenometrics_data.csv" but originally comes from the following link: https://data.usanpn.org/observations

The code used to access the weather data has been included as the file "weather_data_download.py"
