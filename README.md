# data-512-finalProject
Rajiv Veeraraghavan  
December 10th 2017  

# Introduction

In this project, I would like to get a better understanding of the crime patterns in different areas within the city of Seattle. In particular, I would like to understand how crime patterns have evolved over time from 2010 to 2017. 

# Motivation

Based on my limited stay in Seattle (just about a year) and knowledge, I have a feeling that crime rates have increased over the last 6 or so months. I believe getting a better undestanding of the crime patterns and how these patterns are evolving in the city of seattle, the policy departments can take the necessary steps to curb the crime rates. These could include - adding more patrols to certain district in Seattle, reoganize the police department locations across the city, recruit more officers etc.  

Based on my research on the crime trends in Seattle, I am embedding a few articles from the last few months that gives na idea about the current crime trends in Seattle. They seem to suggest an increase in crime for certain types of crime and decrease for other types of crime.

1. http://www.kiro7.com/news/local/man-shot-during-uw-event-for-milo-yiannopoulos/486520649
2. https://www.seattletimes.com/seattle-news/crime/fbi-violent-crime-up-in-seattle-and-washington-in-2016-but-murders-specifically-down/
3. https://patch.com/washington/seattle/seattle-crime-trends-mixed-bag-under-spd-chief-kathleen-otoole

# Dataset and Methodology

The government of Seattle has exposed a dataset which consists of all the 911 incident calls that have taken place from 2010 to 2017. I use the 911 incident calls as a proxy for the crime measure. The datasets consists of information about timestamp, location (latitude, longitude), district name, crime type and a few other attributes to explain the 911 call.

I also use the population data of Seattle to accurately measure the crime rate. To accurately measure crime rate, we can divide the number of 911 calls by population. ( so that we don't want to overestimate the crime rate by just using the number of 911 calls)

I explore these datasets and create visualizations to better understand the crime patterns and trends in the city of Seattle.

# Source of Data

911 Incidents Data -  https://data.seattle.gov/Public-Safety/Seattle-Police-Department-911-Incident-Response/3k2p-39jp (sample of this data is available in the repository)  
Population Data - https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?src=bkmk  

# Licence of the Data

911 Incidents Data -  CC0 1.0 Universal (CC0 1.0) - https://creativecommons.org/publicdomain/zero/1.0/  
Population Data - https://www.census.gov/data/developers/about/terms-of-service.html  

# Google Maps API for heatmap Visualization
One of the visualizaitons in the jupyter notebook leverages the googlemaps heatmap API. You can find more documentations about it here - https://developers.google.com/maps/documentation/javascript/examples/layer-heatmap

This project is licensed under the MIT License - please see the LICENSE file.



