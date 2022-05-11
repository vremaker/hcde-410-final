# hcde-410-final

### Goal
----
This project will look at the distribution of arts and cultures spaces within Seattle based on the Seattle Cultural Space Inventory and the Public Art Database, which show which neighborhoods these spaces show up in. I will also be using the SPD Crime Dataset from 2008 - Present to answer the question: What impact does public arts and cultural spaces have on crime rates, or areas for higher densities of policing? 

### Documentation
----
This project will is viewing 3 databases from the Seattle 

- [**Public Art Database**](https://data.seattle.gov/Community/Public-Art-Data/j7sn-tdzk) which tracks all the public art in Seattle
- [**Seattle Culture Space**](https://data.seattle.gov/Community/Seattle-Cultural-Space-Inventory/vsxr-aydq) which tracks all the spaces for arts and culture in Seattle
- [**SPD Crime Data 2008 - Present**](https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5) which tracks the crime in Seattle 
- [**Seattle Public Spaces**](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::publicspaceseattle-entrypts/explore?location=47.611555%2C-122.355840%2C11.46) which is an overview of parks in Seattle which are open to the public. 

### Data Values of Interest 
----
Because of the scoping of my project, I do not intend to use all of the data values from each of these datasets. In order to give the best overview of my project, I will only be describing values the are directly used to my project. The full description of values in the dataset are  linked in the headers above each list. 

[**Public Art Database**](https://data.seattle.gov/Community/Public-Art-Data/j7sn-tdzk)
- **project:** what the art project is was called (e.g. Ballard Ave)
- **classification:** the art type (e.g. sculpture) 
- **media:** the material that the art piece is made of (e.g. Stained glass)
- **date:** the date which the art piece was erected 
- **location:** the location of the art piece (e.g. Space Needle)


[**Seattle Culture Space**](https://data.seattle.gov/Community/Seattle-Cultural-Space-Inventory/vsxr-aydq)
- **Name:** the name of the space
- **Year:** the year the space was occupied
- **Age of Current Building:** the year the current structure of the spce was
- **Neighborhood:** the neighborhood the space is located in
- **Stage and Theaters:** number of stages/theaters in the space 
- **Gallery Space:** Y/N for if the space has a gallery 
- **Domain Discipline:** the domain that the space is used for (e.g. Music)

[**Seattle Public Spaces**](https://data-seattlecitygis.opendata.arcgis.com/maps/SeattleCityGIS::public-and-open-spaces-in-seattle-1/about)
- **restroom:** whether the park has a restroom
- **public access:** the degree of access/ the time frames for which people can enter the space
- **greenspace:** whether or not there is a lawn
- **status:** is the park open or under construction
- **maintained by:** who is in charge of taking care of the park 
- **public or pirvate:** is this owned by the public? 
- **tier:** the level of the park in ranking, 1 is the highest tier, 6 is the lowest tier


[**SPD Crime Data 2008 - Present**](https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5)
- **Offense:** type of crime (e.g. shoftlifting)
- **MCPP:** police district (e.g. Colombia City)
- **Crime Against Property:** the thing the crimw was against (e.g. Property)

## Issues or Considerations 
After briefly looking through the data, there are a few rows which have missing values, this will need to be a key consideration when working with this data. There may also be issues with the overlap in the city names, and slight synatictical issues, but we are not there yet, and I'm sure something will work out. 
