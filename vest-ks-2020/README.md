# vest-ks-2020

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-kansas-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST KS 2020 file
   - Date accessed: 7/16/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4749664&datasetVersionId=251765
   - File: `ks_2020.zip`
- File: VEST documentation file, 2020
   - Date accessed: 7/16/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4863160&datasetVersionId=251765
   - File: `documentation.txt`
- File: U.S. Census Bureau's 2020 Redistricting Data Program Phase 2 release
  - Date accessed: 7/16/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership20v2/st20_ks.html
  - Note: not downloading these files for the election results validation. 
- File: Sedgwick County Shapefile
  - Date accessed: 7/16/2021
  - Link: https://www.sedgwickcounty.org/gis/data-layers/?altTemplate=gisdatalayer&id=22
  - Note: select 'Download Shapefile'. 
  - File: `sedgewick_election precincts.zip`


### Inaccessible files:
- File: Precinct Level Election results, 2020
  - Date accessed: 7/16/2021
  - Link: https://sos.ks.gov/elections/elections-statistics.html
  - Note: VEST directs us to this website link, however the precinct-level results are not available online. We called 800-262-VOTE(8683) and were directed to email Bryan Caskey (bryan.caskey@ks.gov) to request the precinct-level results. We emailed on 7/16/2021. 
- File: Geary County Shapefile
  - Date accessed: 7/16/2021
  - Link: https://www.gearycounty.org/1312/Polling-Locations
  - Note: select 'Voter Precinct Map (PDF)' on the left. There is not a shapefile available for download on the website. 
- File: Johnson County Shapefile
  - Date accessed: 7/16/2021
  - Link: https://jocoelection.org/maps
  - Note: under 'Online Available Maps', select 'Johnson County City Wards and Voting Precincts'. There is not a shapefile available for download on the website. 
- File: Riley County Shapefile
  - Date accessed: 7/16/2021
  - Link: https://www.rileycountyks.gov/145/Riley-County-Voting-District-Maps
  - Note: there is not a shapefile available for download on the website. 


## File processing:

`vest-ks-2020-validation.ipynb` is the script that is the basis of the validation report
