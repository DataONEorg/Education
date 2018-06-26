---
title: Document and store data using stable file formats
layout: cover_bps
tags:
- documentation
- format
- metadata
- preserve
- storage
- tabular
step:
- describe
related:
- create-and-document
- identify-suitable-repositories
- plan-data-management
update:
- May 08, 2018
author:
- DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---



File formats are important for understanding how data can be used and possibly integrated. The following issues need to be documented:
- Does the file format of the data adhere to one or more standards?
- Is that file standard an open (i.e. open source) or closed (i.e. proprietary) format?
- Is a particular software package required to read and work with the data file? If so, the software package, version, and operating system platform should be cited in the metadata
- Do multiple files comprise the data file structure? If so, that should be specified in the metadata

When choosing a file format, data collectors should select a consistent format that can be read well into the future and is independent of changes in applications.
- Appropriate file types include:
  - Non-proprietary: Open, documented standard
  - Common usage by research community: Standard representation (ASCII, Unicode)
  - Unencrypted
  - Uncompressed
- ASCII formatted files will be readable into the future
  - Use ASCII (comma-separated) for tabular data
- For geospatial (raster) data the following provide a stable format:
  - GeoTIFF/TIFF
  - ASCII Grid
  - Binary image files
  - NetCDF
  - HDF or HDF-EOS
- For image (Vector) data use the following file formats (these are mostly proprietary data formats; please be sure to document the Software Package, Version, Vendor, and native platform):
  - ARCVIEW software -- please store components of an ArcView shape file (*.shp, *.sbx, *.sbn, *.prj, and *.dbf files) ;
  - ENVI -- *.evf (ENVI vector file)
  - ESRI Arc/Info export file (.e00)

## Description Rationale

For long term preservation is it necessary to store data in file formats that will be readable in the future. It is also important to provide descriptive information on these data file types and formats. This will facilitate data retrieval and reuse.

## Additional Information

Data Management and Publishing (MIT Libraries): [https://libraries.mit.edu/data-management/](https://libraries.mit.edu/data-management/)

Burley, T.E., and Peine, J.D., 2009, NBII-SAIN Data Management Toolkit, U.S. Geological Survey Open-File Report 2009-1170, 96 p. Available from: [http://pubs.usgs.gov/of/2009/1170/](http://pubs.usgs.gov/of/2009/1170/)

## Examples

Certain file formats, for example a shapefile, can be made up of as many as 7 individual files. If one of those files is absent from the file assembly the shapefile data utility may be lost. Awareness of adherence to a particular file format standard can also be helpful for determining, for example, if a particular software package can read the data file. Awareness of whether that standard or format is open source or proprietary will also influence how and if the data file can be read.
