---
title: Create, manage, and document your data storage system
layout: bestpractice_cover
tags:
  - access
  - documentation
  - file system
  - metadata
  - plan
step:
  - plan
related:
  - create-and-document
  - plan-data-management
  - plan-for-effective
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
resource: true
categories: ["Best Practice"]
---


Data files should be managed to avoid disorder. To facilitate access to files, all storage devices, locations and access accounts should be documented and accessible to team members. Use appropriate tools, such as version control tools, to keep track of the history of the data files. This will help with maintaining files in different locations, such as at multiple off-site backup locations or servers.

Data sets that result in many files structured in a file directory can be difficult to decipher. Organize files logically to represent the structure of the research/data. Include human readable "readme" files at critical levels of the directory tree. A "readme" file might include such things as explanations of naming conventions and how the structure of the directory relates to the structure of the data.

## Description Rationale

Keeping a managed file storage system will help prevent inconsistencies, e.g., duplicated, lost, or misplaced files.

## Examples

A time series of image files from several remote cameras might be organized so that images from each camera are in different folders. These are, in turn, collected in a folder named "images". Each folder would be named with the identifier for the camera. The file names for images might reflect the time the image was taken.

A "readme" file would document the structure of this system, and document the name scheme to facilitate future curation and automated gathering of metadata.
