---
title: "Data Collection, Entry, and Manipulation"
author: DataONE Community Engagement & Outreach
update: Sept. 22, 2016
layout: slides
---
# Lesson Topics
- Best Practices for Creating Data Files
- Data Entry Options
- Data Integration Best Practices
- Data Manipulation Options

???
In this module we will be looking at best practices as related to the creation of data files.  We will also discuss data entry schemes that help ensure data quality, and data manipulation options

---
# Learning Objectives
- Recognize and plan for inconsistencies that can make a dataset difficult to understand and/or manipulate
- Describe characteristics of stable data formats and list reasons for using these formats
- Identify data entry tools
- Identify validation measures that can be performed as data is entered
- Review best practices for data integration
- Describe the basic components of a relational database
---
# Goals of Data Entry
- Create quality data sets that are:
  - Valid
  - Organized to support ease of use and reuse

???
The goals of data entry are to create data that are valid, or have gone through a process to assure quality, and are organized to support use of the data or for ease of archiving.   
---
# Example: Poor Data Entry


???
These are data entered in to Excel from a small mammal trapping study.   Each block of data represents a different trapping period (2/13, 3/15, and 4/10/2010).  Inconsistencies in how the data were entered for each sampling period  make the data difficult to analyze and difficult for anyone but the data collector to understand.  Note that the date is listed in different places in each block.  Date is a column in the first block, but listed in the header in the block on the right. Inconsistent date formats were also used.  In one place the date is formatted  as day-month-year, with the first three letters of the month spelled out, while elsewhere the format is  mm/dd/yyyy.  Note also that the order of the columns is inconsistent- Site, Date in the first block, and Site, Plot in the bottom block.   Even the columns are named differently.    Species is called Species in the first block, and RodentSp in the block on the right.  This can be confusing to any user who must try to make sense of these data!    And it would be a nightmare to try to write metadata for this spreadsheet.   
---
# Example: Poor Data Entry, continued


???
There are other problems with how these data was entered. Naming of sites is also inconsistent.  For instance, Deep Well is used in the first block vs. DW in the block on the right.  The file contains several typos, also such as rioSalado vs. rioSlado.   A human can figure out what each of these site names refers to, but the names would have to be harmonized for a statistical program to use.   It would be easier to filter for just Deep Well (with a space), and not have to know you need to filter for DeepWell (no space), also.   Similarly, in one place a species code is capitalized PERO, and lowercase elsewhere.   

Further, in the first block of data, a mean was calculated for the weight of the rodents.  The value for that mean, called Mean1, is in the same column as the weights of the individual animals.  In later manipulations of these data, it would be easy to copy that value as though it represented the weight of a single animal.   It is bad practice to mix types of information in one column.   It is best for raw data should be maintained in one file, and calculations should be done elsewhere.   
In addition, there is text data mixed with numeric data in the Weight column in the block on the right – it says “escaped < 15” (presumably indicating that a rodent less than 15 grams escaped).  A statistical program will not know how to deal with text data mixed with numeric data.   What is the mean of 12, 91, and “escaped < 15”?

To analyze all these data using statistical software, and to make it much easier to understand by any user, these data will need to be organized in to a column for each variable.  Therefore it essential that only one type of info be entered in to each column, and that spellings, codes, formats, etc. be consistent.

---
# Recommended Practices
- Columns of data are consistent: only numbers, dates, or text
- Consistent Names, Codes, Formats (date) used in each column
- Data are all in one table, which is much easier for a statistical program to work with than multiple small tables which each require human intervention

???
This shows the same data entered in a way that would make it easy to understand and analyze.  
The data are not entered in separate blocks arrayed in a single worksheet.  They are entered in one table with columns defined by variables Date, Site, Plot, Species, and Weight, Adult, and Comments that are recorded for each sampling event.  

The columns of data have consistent types.   Each column contains only numbers, dates, or text.
There are consistent names, codes, and formats used in each column.  For instance, all dates are in the same format (mm/dd/yyyy), and there are no typos in the Site Names.  Species are all referred to by standard codes.  Therefore, if the user wanted to subset the data for species = `PERO`, they could easily filter the file for just those data.  Additionally,  there are only numeric data in the Weight column, so a statistical program or Excel could readily calculate statistics on this column.    Preparing metadata for this file would also be straightforward.   
---
# Recommended Practices, continued
- Create descriptive column names without spaces or special characters
  - `Soil T30` to `Soil_Temp_30cm`
  - `Species-Code` to "Species_Code (Avoid using -,+,*,^ in column names. Some software may interpret these symbols as an operator)"
- Use a descriptive file name.  For instance, a file named `SEV_SmallMammalData_v.5.25.2010.csv` indicates the project the data is associated with (SEV),  the theme of the data (SmallMammalData) and also when this version of the data was created (v.5.25.2010).   This name is much more helpful than a file named mydata.xls.  

???
One best practice in data entry is to create descriptive column names without spaces or special characters.  Sometimes statistical programs have special uses for some characters, so you should avoid using them in your data file.   
---
# Recommended Practices, continued
- Missing data
  - Preferably leave field empty (NULL = no value)
  - In numeric fields, use a distinct value such as 9999 to indicate a missing value 
  - In text fields, use NA (“Not Applicable” or “Not Available”)
  - Use Data flags in a separate column to qualify missing value

        - M1 = missing; no sample collected, E1 = estimated from grab sample
???
A preferred way to identify missing data is with an empty field. If for some reason an empty cell is not possible then use an impossible value such as 9999 in numeric fields and in text fields use NA.
Use data flags in a separate column to qualify empty cells.  For instance, in this example of stream chemistry data, the flag M1 indicates that the sample was not collected at that interval.   
---
# Recommended Practices, continued
- Enter complete lines of data

???
There are a lot of great things about spreadsheets, but one must be wary of problems that can arise from their use.  Spreadsheets, for instance, can sort one column independently of all others.   The data entry person for the upper spreadsheet elected to leave empty cells for site, treat, web, plot, quad.  It’s obvious why and doesn’t cause the human reader any problems.  But if someone happens to decide to sort on Species, it is no longer clear which species maps to which time period or to which measurements.  This could make the spreadsheet unusable.   It is good practice to fill in all cells when using a spreadsheet for data entry.   
A best practice is to enter complete lines of data, so that the data are sorted on one column without loss of information
---
# Best Practices
- For the long term, store data in a consistent format that can be read well in to the future and that can be used by any application now or in the future 
- Appropriate file types include:
  - Non-proprietary: use an open, documented standard 
  - Common usage by research community: Standard representation (ASCII, Unicode) 
  - Unencrypted 
  - Uncompressed
- ASCII formatted files are likely to be readable into the future
  - Use ASCII (comma-separated) for tabular data

???
Archiving your data publicly will require that it be stored in a non-proprietary format such as ASCII.   A common practice is to store data in a comma-delimited text file.   There have been many instances where data sets have been lost because they were stored in a proprietary format which becomes obsolete.  
---




