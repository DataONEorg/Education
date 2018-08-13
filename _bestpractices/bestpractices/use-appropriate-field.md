---
title: Use appropriate field delimiters
layout: bestpractice_cover
tags:
  - access
  - collect
  - describe
  - format
step:
  - collect
  - describe
related:
  - consider-the-compatability
  - identify-and-use
  - use-consistent-codes
update:
  - September 01, 2011
author:
  - DataONE Best Practices Working Group
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
resource: true
categories: ["Best Practice"]
---


Delimit the columns within a data table using commas or tabs; these are listed in order of preference. Semicolons are used in many systems as line end delimiters and may cause problems if data are imported into those systems (e.g. SAS, PHP scripts). Avoid delimiters that also occur in the data fields. If this cannot be avoided, enclose data fields that also contain a delimiter in single or double quotes.

An example of a consistently delimited data file with a header row:

Date, Avg Temperature, Precipitation  
01Jan2010, 32.3, 0.0  
02Jan2010, 34.1, 0.5  
03Jan2010, 31.4, 2.5  
04Jan2010, 33.2, 0.0

## Description Rationale

Consistent use of preferred field delimiters (e.g., comma separated variables) enables data tables to be easily incorporated into analytical and other software programs and ensures that the data content and structure are preserved.

## Additional Information

Best Practices for Preparing Environmental Data Sets to Share and Archive, (formerly Cook et al., 2001) Updated by L. A. Hook, T. W. Beaty, S. Santhana-Vannan, L. Baskaran, and R. B. Cook. June 2007. [http://daac.ornl.gov/PI/bestprac.html](http://daac.ornl.gov/PI/bestprac.html)
