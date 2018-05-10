---
title: Assign descriptive file names
layout: bestpractice
tags:
  - access
  - describe
  - discover
  - format
related:
  - Choose-and-use
  - Confirm-a-match
  - Describe-the-contents
---

## Best practice

File names should reflect the contents of the file and include enough information to uniquely identify the data file. File names may contain information such as project acronym, study title, location, investigator, year(s) of study, data type, version number, and file type.

When choosing a file name, check for any database management limitations on file name length and use of special characters. Also, in general, lower-case names are less software and platform dependent. Avoid using spaces and special characters in file names, directory paths and field names. Automated processing, URLs and other systems often use spaces and special characters for parsing text string. Instead, consider using underscore ( _ ) or dashes ( - ) to separate meaningful parts of file names. Avoid $ % ^ & # | : and similar.

If versioning is desired a date string within the file name is recommended to indicate the version.

Avoid using file names such as mydata.dat or 1998.dat.

## Description Rationale

Clear, descriptive, and unique file names may be important when your data file is combined in a directory or FTP site with your own data files or with the data files of other investigators. File names that reflect the contents of the file and uniquely identify the data file enable precise search and discovery of particular files.

## Related Best Practices

- Choose and use standard terminology to enable discovery
- Confirm a match between data and their description in metadata
- Describe the contents of data files

## Additional Information

Hook, Les A., Suresh K. Santhana Vannan, Tammy W. Beaty, Robert B. Cook, and Bruce E. Wilson. 2010. Best Practices for Preparing Environmental Data Sets to Share and Archive. Available online http://daac.ornl.gov/PI/BestPractices-2010.pdf from Oak Ridge National Laboratory Distributed Active Archive Center, Oak Ridge, Tennessee, U.S.A. doi:10.3334/ORNLDAAC/BestPractices-2010

Borer et al. 2009. Some Simple Guidelines for Effective Data Management. Bull. of ESA 90: 209-214.

## Examples

- An example of a good data file name:
Sevilleta_LTER_NM_2001_NPP.csv
Sevilleta_LTER is the project name
NM is the state abbreviation
2001 is the calendar year
NPP represents Net Primary Productivity data
csv stands for the file type—ASCII comma separated variable
- Instead of "data May2011" use "data_May2011" or "data-May2011"
