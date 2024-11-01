New York 2022 Select Educational Attainment Data from the American Community Survey (2018-2022) at the Block Group level

##Redistricting Data Hub (RDH) Retrieval Date
03/13/24

##Sources
ACS data retrieved using the Census API: https://api.census.gov/data/2022/acs/acs5
Boundary shapefile retrieved from the Census Cartographic Boundary File website: https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.2022.html

##Fields
Field Name Description                                                                                                                                                                                                                                                      
GEOID      Unique Geographic Identifier                                                                                                                                                                                                                                     
STATEFP    State FIPS                                                                                                                                                                                                                                                       
STATE      State Name                                                                                                                                                                                                                                                       
COUNTYFP   County FIPS                                                                                                                                                                                                                                                      
COUNTY     County Name                                                                                                                                                                                                                                                      
POP_25OV22 Total population 25 years and over (B15003_001E)                                                                                                                                                                                                                 
N_HSDIP22  Less than a high school diploma, GED or equivalent (sum of B15003_002E, B15003_003E, B15003_004E, B15003_005E, B15003_006E, B15003_007E, B15003_008E, B15003_009E, B15003_010E, B15003_011E, B15003_012E, B15003_013E, B15003_014E, B15003_015E, and B15003_016E)
HS_DIP22   High school diploma, GED or equivalent (sum of B15003_017E and B15003_018E)                                                                                                                                                                                      
SOM_COLL22 Some college, no degree (sum of B15003_019E and B15003_020E)                                                                                                                                                                                                     
ASSO_DEG22 Associates Degree (B15003_021E)                                                                                                                                                                                                                                  
BACH_DEG22 Bachelor's Degree (B15003_022E)                                                                                                                                                                                                                                  
MAST_DEG22 Master's Degree (B15003_023E)                                                                                                                                                                                                                                    
PROF_DEG22 Professional school degree (B15003_024E)                                                                                                                                                                                                                         
DOCT_DEG22 Doctorate degree (B15003_025E)                                                                                                                                                                                                                                   

##Processing
ACS data for New York was retrieved with a Python script from the Census API.
The block group data is available by county for all counties in New York. The script extracted the data for all counties in New York. 
Each field represents an estimate from the Census for a particular variable or sum of variables, as noted in the Fields section above.
The data were then merged on the GEOID with a corresponding TIGER shapefile.

##Additional Notes
The counts of individuals by educational attainment are for the population of people 25 years and older.
For any questions about this dataset or if you would like additional related ACS data, please email info@redistrictingdatahub.org.