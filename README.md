## Yeast project

## Summary

Provide a brief description of the project - 150 words.

## Highly Qualified Personnel

- Name, Institution, email, ORCID 0000-0000-0000-0000

## Principle Investigators

- Douglas A. Campbell, Mount Allison University, dcampbel@mta.ca, ORCID 0000-0001-8996-5463

## Primary Contact  

- Douglas A. Campbell, Mount Allison University, dcampbel@mta.ca, ORCID 0000-0001-8996-5463

## Data sources

- Provide links to any data used from external providers .


## Keywords

List keywords separated by commas

## Additional information and support

- Sensitive Data Flag - Human Participants:  NO
- Sensitive Data Flag - Indigenous Partnerships: YES or NO
- Sensitive Data Flag - Government Partnerships: YES or NO
- Sensitive Data Flag - Industry Partnerships: NO
- Access Restrictions

## Software  

The software (and version) used to create the dataset.  

## Repo content information

Use the space below to summarize the structure of the repository with a decription of each folder, as applicable.

### MetaDataCatalog
URL for MetaDataCatalog, or MetaDataCatalog filename
example:
https://docs.google.com/spreadsheets/d/1rlj03Q_wq83qlyiY7mXq8BK6C-L0Ko799JsyhfA1TGI/edit#gid=0
Use standard variable names for MetaDataCatalog

### Data Dictionary
URL for Data Dictionary, or Data Dictionary filename
example:
https://docs.google.com/spreadsheets/d/1KzHZETwASnt4XW69HYufHwlWaE_E-yHkLDqetiOYqBg/edit#gid=671854404

### Data/RawData

Raw data files in various formats. Original files generated by analytical equipment, received from a data provider or outside contractor, etc.
Subfolders contain files from a single instrument.
Do not create swarms of superfluous sub-folders.

### Data/CleanData

Clean data in formats for long-term storage. Modified data with the appropriate column/row headers and data structure.

### Data/ProcessedData

Processed data in formats for long-term storage.

### Code
 
Scripts for processing raw data into cleaned data, outside derived code, and user derived code.
A folder OldR is used to store outdated code.
Typically organize .Rmd in modules; Import; Tidy; Process saving .Rds out of each step.


This .Rmd imports Molecular Device Absorbance data, with data reorganized into columns labelled by treatment.


### Docs

Project notes, other documentation, etc.

### Output

Output from knit .Rmd, Figures and tables produced from analysis.
Do not generate swarms of superfluous data exploration figures.
