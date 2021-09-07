# vest-ks-2018

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-kansas-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST KS 2018 file
   - Date accessed: 8/23/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4302290&datasetVersionId=251384
   - File: `ks_2018.zip`
- File: VEST documentation file, 2018
   - Date accessed: 8/23/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4863187&version=41.0
   - File: `documentation.txt`
- File: U.S. Census Bureau's 2020 Redistricting Data Program Phase 2 release
  - Date accessed: 8/23/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership20v2/st20_ks.html
  - Note: not downloading these files for the election results validation. 
- File: Precinct Level Election results, 2018
  - Date accessed: 8/23/2021
  - Link: https://sos.ks.gov/elections/elections-results.html
- File: Precinct Level Election results for Wyandotte County, 2018
  - Date accessed: 9/7/2021
  - Link: https://raw.githubusercontent.com/openelections/openelections-data-ks/master/2018/20181106__ks__general__precinct.csv
  - Note: VEST did not use this file, they had access to the SOS results

### Inaccessible files:
- File: SOS Precinct Level Election results for Wyandotte County, 2018
  - Note: we emailed Bryan Caskey from the KS SOS twice and called the office twice over the course of 1.5 months and did not receive this file or hear back. 
- File: Geary County Shapefile
  - Date accessed: 8/23/2021
  - Link: https://www.gearycounty.org/1312/Polling-Locations
  - Note: select 'Voter Precinct Map (PDF)' on the left. There is not a shapefile available for download on the website. 
- File: Johnson County Shapefile
  - Date accessed: 8/23/2021
  - Link: https://jocoelection.org/maps
  - Note: under 'Online Available Maps', select 'Johnson County City Wards and Voting Precincts'. There is not a shapefile available for download on the website. 
- File: Riley County Shapefile
  - Date accessed: 8/23/2021
  - Link: https://www.rileycountyks.gov/145/Riley-County-Voting-District-Maps
  - Note: there is not a shapefile available for download on the website. 


## File processing:

`vest-ks-2018-validation.ipynb` is the script that is the basis of the validation report
