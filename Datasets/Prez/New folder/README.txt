New York 2022 Select Poverty Data from the American Community Survey (2018-2022) at the Block Group level

##Redistricting Data Hub (RDH) Retrieval Date
03/14/24

##Sources
ACS data retrieved using the Census API: https://api.census.gov/data/2022/acs/acs5

##Fields
Field Name Description                                                                                                                                                                 
GEOID      Unique Geographic Identifier                                                                                                                                                
STATEFP    State FIPS                                                                                                                                                                  
STATE      State Name                                                                                                                                                                  
COUNTYFP   County FIPS                                                                                                                                                                 
COUNTY     County Name                                                                                                                                                                 
TOT_HOUS22 Total households (B17010_001E)                                                                                                                                              
TOT_CHI22  Total households with related children under the age of 18 (sum of B17010_004E, B17010_011E, B17010_017E, B17010_024E, B17010_031E, and B17010_037E)                        
TOT_MAR22  Total married-couple households with related children under the age of 18 (sum of B17010_004E and B17010_024E)                                                              
TOT_MAL22  Total households with a male householder (no spouse present) with related children under the age of 18 (sum of B17010_011E and B17010_031E)                                 
TOT_FEM22  Total households with a female householder (no spouse present) with related children under the age of 18 (sum of B17010_017E and B17010_037E)                               
TOT_BPOV22 Total households with income in the past 12 months below poverty level (B17010_002E)                                                                                        
CHI_BPOV22 Total households with related children under the age of 18 with income in the past 12 months below poverty level (sum of B17010_004E, B17010_011E, and B17010_017E)         
MAR_BPOV22 Total married-couple households with related children under the age of 18 with income in the past 12 months below poverty level (B17010_004E)                               
MAL_BPOV22 Total households with a male householder (no spouse present) with related children under the age of 18 with income in the past 12 months below poverty level (B17010_011E)  
FEM_BPOV22 Total households with a female householder (no spouse present) with related children under the age of 18 with income in the past 12 months below poverty level (B17010_017E)
TOT_APOV22 Total households with income in the past 12 months above poverty level (B17010_022E)                                                                                        
CHI_APOV22 Total households with related children under the age of 18 with income in the past 12 months above poverty level (sum of B17010_024E, B17010_031E, and B17010_037E)         
MAR_APOV22 Total married-couple households with related children under the age of 18 with income in the past 12 months above poverty level (B17010_024E)                               
MAL_APOV22 Total households with a male householder (no spouse present) with related children under the age of 18 with income in the past 12 months above poverty level (B17010_031E)  
FEM_APOV22 Total households with a female householder (no spouse present) with related children under the age of 18 with income in the past 12 months above poverty level (B17010_037E)
TOT_CVAP22 Total Citizen Voting Age Population (CVAP) (B29003_001E)                                                                                                                    
BPV_CVAP22 Total CVAP with income in the past 12 months below poverty level (B29003_002E)                                                                                              
APV_CVAP22 Total CVAP with income in the past 12 months above poverty level (B29003_003E)                                                                                              

##Processing
ACS data for New York was retrieved with a Python script from the Census API.
The block group data is available by county for all counties in New York. The script extracted the data for all counties in New York. 
Each field represents an estimate from the Census for a particular variable or sum of variables, as noted in the Fields section above.

##Additional Notes
For any questions about this dataset or if you would like additional related ACS data, please email info@redistrictingdatahub.org.