**Meta Data Name**: 2018 Other demographic variables, part of the Demographic Social dataset  
**Last Modified**: October 22nd, 2020  
**Author**: Moksha Menghaney  

### Data Location: 
DS01 - Policy Scan Environment Report at 4 spatial scales. Files can be found [here](https://github.com/GeoDaCenter/opioid-policy-scan/tree/master/Policy_Scan/data_final).
* DS01_T  
* DS01_Z  
* DS01_C  
* DS01_S  

### Data Source(s) Description:  
Variables were obtained from the 2014 - 2018 American Community Survey (ACS), table B06009, DP02, at State, County, Tract and ZIP Code Tabulation Area level. Raw data and more details can be found at https://data.census.gov.

### Description of Data Source Tables:
B06009 : Place of birth by Educational Attainment <br>
DP02 : Selected Social Characteristics, provides the percentage of disabled population

### Description of Data Processing: 
The following variables were included from **B06009**:
  1. Estimate; Total Population 25 years and over in the United States
  2. Estimate; Educational Attainment  – Less than high school graduate (for population 25 years and over)
  
The following variables were included from **DP02**:
  1. Percent Estimate; Disability Status of the Civilan NonInstitutionalized Population

----------
* Percentage of population with less than a high school degree was calculated as: *estimate for the group / total population of age 25 years and over*

### Key Variable and Definitions:
| Variable | Variable ID in .csv | Description |
|:---------|:--------------------|:------------|
| % Less than High School degree  | noHSP | Percentage of population 25 years and over, less than a high school degree |
| % Population Disabled  | disbP | Percentage of civilian non institutionalized population with a disability |

### Data Limitations:
n/a

### Comments/Notes:
n/a