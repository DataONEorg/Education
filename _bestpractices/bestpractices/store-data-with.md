---
title: Store data with appropriate precision
layout: bestpractice
tags:
  - analyze
  - measurement
  - preserve
  - storage
 step:
  - analyze
  - preserve
related:
  - backup-your-data
  - create-manage-and
  - define-roles-and
---

## Best Practice
Data should not be entered with higher precision than they were collected in (e.g if a device collects data to 2dp, an Excel file should not present it to 5 dp). If the system stores data in higher precision, care needs to be taken when exporting to ASCII. E.g. calculation in Excel will be done to the highest possible precision of the system, which is not related to the precision of the original data.
