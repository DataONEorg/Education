---
title: "Preserve information: keep raw data raw"
layout: cover_bps
tags:
  - collect
  - data consistency
  - format
  - preserve
step:
  - collect
  - preserve
related:
  - backup-your-data
  - use-appropriate-field
  - use-consistent-codes
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---



In order to preserve the raw data for future use:

- Do not make any changes / corrections to the original raw data file
- Use a scripted language (e.g., R) or a software language that can be documented (eg., C, Java, Python, etc.) to perform analysis or make corrections and save that information in a separate file
    - The code, along with appropriate documentation will be a record of the changes
    - The code can be modified and rerun, using the raw data file as input, if needed
- Consider making your original data file read-only, so it cannot be inadvertently altered.
- Avoid spreadsheet software and other Graphical User Interface-based software. They may seem convenient, but changes are made without a clear record of what was done or why. Spreadsheets provide incredible freedom and power for manipulating data, but if used inappropriately can create tremendous problems. For this reason special attention needs to be paid to adhering to best practices in organizing data in spreadsheets. Particularly important best practices that are also highlighted elsewhere are:
    - Data should be organized in columns with each column representing only a single type of data (number, date, character string. An exception to this is that sometimes a header line containing column names (sometimes called variable or field names) may be placed at the top of a column.
    - Each data line should be complete, that is, each line of the data should contain data for each column. Sometimes in spreadsheets, to promote human readability, values will be provided only when they change. However, if the data is sorted, the relationships would become scrambled. An exception to this rule is if a data item is really missing (and not just omitted for human readability)a missing value code might be used.
Additional best practices regarding consistent use of codes for categorical variables, and informative field names also apply, but keeping the data in consistent and complete columns are the most important.

A key test is whether the data from a spreadsheet can be exported as a delimited text file, such as a comma-separated-value (.csv) file that can be read by other software. If columns are not consistent the resulting data may cause software such as relational databases (e.g., MySQL, Oracle, Access) or statistical software (e.g., R, SAS, SPSS) to record errors or even crash.

As a general rule, spreadsheets make a poor archival data format. Standards for spreadsheet file formats change frequently or go out of fashion. Even within a single software package (e.g., Excel) there is no guarantee that future versions of the software will read older file versions. For this reason, and as specified in other best practices, generic (e.g., text) formats such as comma-separated-value files are preferred.

Sometimes it is the formulae embedded in a spreadsheet, rather than the data values themselves that are important. In this case, the spreadsheet itself may need to be archived. The danger of the spreadsheet being rendered obsolete or uninterpretable may be reduced by exporting the spreadsheet in a variety of forms (e.g., both as .xls and as .xlsx formats). However the long-term utility of the spreadsheet may still depend on periodic opening of the archived spreadsheet and saving it into new forms.

Upgrades and new versions of software applications often perform conversions or modifications to data files produced in older versions, in many cases without notifying the user of the internal change(s).

Many contemporary software applications that advertise forward compatibility for older files actually perform significant modifications to both visible and internal file contents. While this is often not a problem, there are cases where important elements like numerical formulas in a spreadsheet, are changed significantly when they are converted to become compatible with a current software package. The following practices will help ensure that your data files maintain their original fidelity in the face of application updates and new releases:

   - Where practical, continue using the version of the software that was originally used to create the data file to view and manipulate the file contents (For example, if Excel 97 was used to create a spreadsheet that contains formulas and formatting, continue using Excel 97 to access those data files as long as possible).
   - When forced to use a newer version of a software package to open files created with an older version of the application, first save a copy of the original file as a safeguard against irretrievable modification or corruption.
   - Carefully inspect older files that have been opened/converted to be compatible with newer versions of an application to ensure data fidelity has been carried forward. Where possible, compare the converted files to copies of the original files to ensure there have been no data modifications during conversion.

## Description Rationale

Preserve the information content of your original raw data.

## Related Best Practices

- Backup your data
- Use appropriate field delimiters
- Use consistent codes

## Additional Information

Borer, E. T., Seabloom, E. W., Jones, M. B., & Schildhauer, M. 2009. Some Simple Guidelines for Effective Data Management. Bull. of ESA 90: 209-214. https://doi.org/10.1890/0012-9623-90.2.205
