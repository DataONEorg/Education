---
title: Describe formats for date and time
layout: cover_bps
tags:
- date
- describe
- format
- standards
- time
step:
- describe
related:
- choose-and-use
- consider-the-compatibility
- use-consistent-codes
update:
- May 08, 2018
author:
- DataONE Community Engagement & Outreach Working Group
resource: true
---

## Best Practice
For date, always include four digit year and use numbers for months. For example, the date format yyyy-mm-dd would appear as 2011-03-15 (March 15, 2011).

If Julian day is used, make sure the year field is also supplied. For example, mmm.yyyy would appear as 122.2011, where mmm is the Julian day.

If the date is not completely known (e.g. day not known) separate the columns into parts that do exist (e.g. separate column for year and month). Don't introduce a day because the database date format requires it.

For time, use 24-hour notation (13:30 hrs instead of 1:30 p.m. and 04:30 instead of 4:30 a.m.). Report in both local time and Coordinated Universal Time (UTC). Include local time zone in a separate field. As appropriate, both the begin time and end time should be reported in both local and UTC time. Because UTC and local time may be on different days, we suggest that dates be given for each time reported.

Be consistent in date and time formats within one data set.

## Description Rationale
The date and time are important pieces of contextual information for observations. A complete description of date and time allows the observation to be used and interpreted properly.

## Related Best Practices
- Choose and use standard terminology to enable discovery
- Consider the compatibility of the data you are integrating
- Use consistent codes

## Additional Information
ISO 8601 format date: YYYY-MM-DD time: HH:MM:SS datatime: YYYYMMDDTHHMMSS
