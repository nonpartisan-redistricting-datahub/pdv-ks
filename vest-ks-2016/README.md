# vest-ks-2016

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-kansas-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST KS 2016 file
   - Date accessed: 9/7/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4749662&version=67.0
   - File: `ks_2016.zip`
- File: VEST documentation file, 2016
   - Date accessed: 9/7/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5007728&version=67.0
   - File: `documentation.txt`
- File: U.S. Census Bureau's 2020 Redistricting Data Program Phase 2 release
  - Date accessed: 9/7/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership20v2/st20_ks.html
  - Note: not downloading these files for the election results validation. 
- File: Precinct Level Election results, 2016
  - Date accessed: 9/7/2021
  - Link: https://sos.ks.gov/elections/elections-results.html
- File: Precinct Level Election results for Wyandotte, Johnson, Sedgwick, and Shawnee Counties, 2016
  - Date accessed: 9/7/2021
  - Link: https://github.com/openelections/openelections-data-ks/tree/master/2016/counties


### Inaccessible files:
- File: Geary County Shapefile
  - Date accessed: 9/7/2021
  - Link: https://www.gearycounty.org/1312/Polling-Locations
  - Note: select 'Voter Precinct Map (PDF)' on the left. There is not a shapefile available for download on the website. 
- File: Johnson County Shapefile
  - Date accessed: 9/7/2021
  - Link: https://jocoelection.org/maps
  - Note: under 'Online Available Maps', select 'Johnson County City Wards and Voting Precincts'. There is not a shapefile available for download on the website. 
- File: Riley County Shapefile
  - Date accessed: 9/7/2021
  - Link: https://www.rileycountyks.gov/145/Riley-County-Voting-District-Maps
  - Note: there is not a shapefile available for download on the website. 


## File processing:

`vest-ks-2016-validation.ipynb` is the script that is the basis of the validation report
