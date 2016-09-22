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

