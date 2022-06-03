# Greenspace and Crime in Seattle

### Goal
----
This project will look at the rates of crime within Seattle's neighborhoods as well as the distribution of natural spaces (and their quality) to answer the question: What impact does access to nature have on crime rates? 

### Documentation 
----
This project focuses on three databases to understand the distribution of crime and greenspace. [Find more about the open data lisencence](https://www.seattle.gov/tech/initiatives/open-data)

- [**SPD Crime Data 2008 - Present**](https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5) which tracks the crime in Seattle crime. In this study, I will be focusing on the year 2022 specf 
- [**Seattle Public Spaces**](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::publicspaceseattle-entrypts/explore?location=47.611555%2C-122.355840%2C11.46) which is an overview of parks in Seattle which are open to the public. 
- [**Seattle Neighborhood GeoData**](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::city-clerk-neighborhoods/about) which breaks the Seattle area into different neighborhoods based on Geodata. 

### Data Values of Interest 
----
Because of the scoping of my project, I do not intend to use all of the data values from each of these datasets. In order to give the best overview of my project, I will only be describing values the are directly used to my project. The full description of values in the dataset are  linked in the headers above each list. 

[**Seattle Public Spaces**](https://data-seattlecitygis.opendata.arcgis.com/maps/SeattleCityGIS::public-and-open-spaces-in-seattle-1/about)
- **public access:** the degree of access/ the time frames for which people can enter the space
- **public or private:** whether the space is open to the public
- **natural:** whether the space has natural elements
- **greenspace:** whether or not there is a lawn
- **status:** whether the park is open
- **tier:** the level of the park in ranking, 1 is the highest tier, 6 is the lowest tier
- **longitude:** the longitude for the parks location
- **latitude:** the latitude for the parks location 

[**Seattle Neighborhood GeoData**](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::city-clerk-neighborhoods/about) 
- **L_HOOD:** the name of the larger neighborhood
- **geometry:** the geodata for the locaiton and shape of the neighborhood 

[**SPD Crime Data 2008 - Present**](https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5)
- **longitude:** the longitude for the parks location
- **latitude:** the latitude for the parks location 
- **report date time:** when the crime was reported

## Issues or Considerations 
When we think about data, it is critical to think about the third variable problem, in which we cannot attribute all of these findings to crime and greenspace itself. It could have to do with things like: population in a neighborhood, size of the neighborhood, socioeconomic status within a neighborhood, and the ratio of stores, housing and natural space in a neighborhood. 