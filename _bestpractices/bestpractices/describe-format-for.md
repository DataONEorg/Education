---
title: Describe format for spatial location
layout: cover_bps
tags:
- access
- describe
- format
- geospatial
- location
step:
- describe
related:
- describe-formats-for
- describe-method-to
- use-consistent-codes
update:
- May 08, 2018
author:
- DataONE Community Engagement & Outreach Working Group
resource: true
---


Spatial coordinates should be reported in decimal degrees format to at least 4 (preferably 5 or 6) significant digits past the decimal point. An accuracy of 1.11 meters at the equator is represented by +/- 0.00001. This does not include uncertainty introduced by a GPS instrument.

Provide latitude and longitude with south latitude and west longitude recorded as negative values, e.g., 80 30' 00" W longitude is -80.5000.

Make sure that all location information in a file uses the same coordinate system, including coordinate type, datum, and spheroid. Document all three of these characteristics (e.g., Lat/Long decimal degrees, NAD83 (North American Datum of 1983), WGRS84 (World Geographic Reference System of 1984)). Mixing coordinate systems [e.g., NAD83 and NAD27 (North American Datum of 1927)] will cause errors in any geographic analysis of the data.

If locating field sites is more convenient using the Universal Transverse Mercator (UTM) coordinate system, be sure to record the datum and UTM zone (e.g., NAD83 and Zone 15N), and the easting and northing coordinate pair in meters, to ensure that UTM coordinates can be converted to latitude and longitude.

To assure the quality of the geospatial data, plot the locations on a map and visually check the location.

## Description Rationale
Spatial information is necessary to describe where on Earth an observation was made.

## Related Best Practices
1. Describe formats for date and time
2. Describe method to create derived data products
3. Use consistent codes
