---
title: Define the parameters
layout: bestpractice_cover
tags:
- describe
- documentation
- metadata
- parameter
step:
- describe
related:
- define-the-data
- plan-data-management
- use-consistent-codes
update:
  - July 01, 2010
author:
  - DataONE Best Practices Working Group
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
resource: true
categories: ["Best Practice"]
---


The parameters reported in the data set need to have names that clearly describe the contents. Ideally, the names should be standardized across files, data sets, and projects, in order that others can readily use the information.

The documentation should contain a full description of the parameter, including the parameter name, how it was measured, the units, and the abbreviation used in the data file.

A missing value code should also be defined. Use the same notation for each missing value in the data set. Use an extreme value (-9999) and do not use character codes in a numeric field. Supply a flag or a tag in a separate field to define briefly the reason for the missing data.

Within the data file use commonly accepted abbreviations for parameter names, for example, Temp for temperature, Precip for precipitation, Lat and Long for latitude and longitude. See the references in the Bibliography for additional examples. Some systems still have length limitations for column names (e.g.13 characters in ArcGIS); lower case column names are generally more transferrable between systems; Space and special characters should not be used in attribute names. Only numbers, letters, and underscores (“_”) transfer easily between systems.

Also, be sure to use consistent capitalization (not temp, Temp, and TEMP in the same file).

## Description Rationale

In order for others to use your data, they must fully understand the parameters in the data set, including the parameter name, unit of measure, and format.

## Additional Information

Hook, Les A., Suresh K. Santhana Vannan, Tammy W. Beaty, Robert B. Cook, and Bruce E. Wilson. 2010. Best Practices for Preparing Environmental Data Sets to Share and Archive. Available online ([http://daac.ornl.gov/PI/BestPractices-2010.pdf](http://daac.ornl.gov/PI/BestPractices-2010.pdf)) from Oak Ridge National Laboratory Distributed Active Archive Center, Oak Ridge, Tennessee, U.S.A. [http://doi.org/10.3334/ORNLDAAC/BestPractices-2010](http://doi.org/10.3334/ORNLDAAC/BestPractices-2010)

Cook et al., 2001. Best Practices for Preparing Ecological and Ground-Based Data Sets to Share and Archive. Bulletin of ESA 82: 138-141.

Borer et al. 2009. Some Simple Guidelines for Effective Data Management. Bulletin of ESA 90: 209-214. [http://doi.org/10.1890/0012-9623-90.2.205](http://doi.org/10.1890/0012-9623-90.2.205)
