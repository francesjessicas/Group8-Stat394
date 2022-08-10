# Data folder
Lake water quality data from
https://www.stats.govt.nz/indicators/modelled-lake-water-quality/


Need to answer this. Do explanation of where data from, what each variable means...................
I expect a mostly textual description of the data set: what is is about, where did you find it, what's your motivation, its availability. A initial guiding question, based on what you've learned from looking at the data set would be interesting, even if very broad at this stage.



The data contains modelled median values for 

The data we have chosen to use is a Stats NZ dataset on modelled lake water quality. There are 3820 lakes in New Zealand that have a surface area larger than one hectare. Of these, only 18 lakes had incomplete observations, so 3802 lakes are included in the sample. No lakes in offshore islands of New Zealand are included in this dataset. For each lake, modelled median values for the period 2013 to 2017 were recorded for each of the six measures; Ammoniacal Nitrogen, Chlorophyll-a, Total Nitrogen, Total Phosphorus, water Clarity and Trophic level index. Measures of the perimeter (in metres), depth (in metres), area (in square metres) and New Zealand map grid coordinates (both easting and northing) where recorded as well as the ID of the lake, the region it is in, the dominant landcover and the lake type. The name of some lakes were also recorded. 

Ammoniacal Nitrogen is a form of nitrogen that supports algae and plant growth, but in large concentrations can be toxic to aquatic life. 


We have edited this data slightly. Previously, Ammoniacal Nitrogen, Chlorophyll-a, Total nitrogen, Total phosphorus, Water clarity and Trophic level index were categories in a variable called 'measure', and the values for each were all recorded in a variable called 'median'. We wanted to be able to compare levels of some of these variables to see if there was a relationship between any pairs. To be able to do this, we made a new variable for each measure, with their values recorded in their own variables, along with some categorical variables indicating the band classification and whether the observation exceeded the national bottom line for that measure (if there is one). In this new set of data, each lake has a single observation, as opposed to the six or more each had before the data was truncated. No observations were changed and all 3802 lakes had observations for each of the six measures. 
