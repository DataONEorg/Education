---
title: Confirm a match between data and their description in metadata
layout: bestpractice
tags:
  - assure
  - data consistency
  - describe
  - documentation
  - metadata
  - quality
step:
  - assure
  - describe
related:
  - consider-the-compatibility
  - describe-the-contents
  - define-the-data
---

## Best practice

To assure that metadata correctly describes what is actually in a data file, visual inspection or analysis should be done by someone not otherwise familiar with the data and its format. This will assure that the metadata is sufficient to describe the data. For example, statistical software can be used to summarize data contents to make sure that data types, ranges and, for categorical data, values found, are as described in the documentation/metadata.

## Description Rationale

Sometimes mistakes in either data or metadata preparation cause discrepancies between the two. These can include missing (or extra) columns of data, mis-ordered columns of data, or discrepant values. 

## Related Best Practices

  - Consider the compatibility of the data you are integrating
  - Describe the contents of data files
  - Define the data model

## Additional Information

- Lin, C.C, Porter JH, Hsiao C.W, Lu S.S, Jeng M.R. Establishing an EML-based Data Management System for Automating Analysis of Field Sensor Data. Taiwan J For Sci. 23(3):279-285, 2008.
http://www.tfri.gov.tw/enu/pub_science_in.aspx?pid=895&catid0=43&catid1=140&pg0=&pg1=1
- Long, J.B. Validating Metadata at the VCR/LTER. LTER Databits, Spring 2011.
http://databits.lternet.edu/spring-2011/validating-metadata-vcrlter

## Examples

Metadata describes a dataset that has two columns, the first is defined to be StationID and should contain station codes "Station1" and "Station2." The second column contains temperature data with a range between -20 and 40 degrees Celsius. However, the data file contains three columns. The first contains the temperature, the second humidity and the third the StationID with stations labled "Stat1", "Stat2", and "Stat3". This sort of problem can occur if data is processed or added after initial metadata was created, or if there were simply mistakes made in the metadata preparation. Having a naive user use the metadata to ingest and analyze this data will make the problems clear and either the metadata or the data can be altered to make it so they correspond.
