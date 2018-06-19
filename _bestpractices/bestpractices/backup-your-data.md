---
title: Backup your data
layout: cover_bps
tags:
  - access
  - preserve
  - disaster recovery
step:
  - access
  - preserve
related:
  - create-and-document
  - define-the-data
  - identify-suitable-repositories
update:
  - May 08, 2018
author:
  - DataONE Community Engagement & Outreach Working Group
resource: true
---


To avoid accidental loss of data you should:

- Backup your data at regular frequencies
  - When you complete your data collection activity
  - After you make edits to your data
- Streaming data should be backed up at regularly scheduled points in the collection process
  - High-value data should be backed up daily or more often
  - Automation simplifies frequent backups
- Backup strategies (e.g., full, incremental, differential, etc…) should be optimized for the data collection process
- Create, at a minimum, 2 copies of your data
- Place one copy at an “off-site” and “trusted” location
  - Commercial storage facility
  - Campus file-server
  - Cloud fire-server (e.g., Amazon S3, Carbonite)
- Use a reliable device when making backups
  - External USB drive (avoid the use of “light-weight” devices e.g., floppy disks, USB stick-drive; avoid network drives that are intermittently accessible)
  - Managed network drive
  - Managed cloud file-server (e.g., Amazon S3, Carbonite)
- Ensure backup copies are identical to the original copy
  - Perform differential checks
  - Perform “checksum” check
- Document all procedures to ensure a successful recovery from a backup copy

## Description Rationale

To avoid data loss, and to retain information held in earlier versions, it is valuable to back-up your data at frequent intervals and in multiple locations.

## Related Best Practices
- Create and document a data backup policy
- Define the data model
- Identify suitable repositories for the data

## Additional Information:
http://en.wikipedia.org/wiki/Backup  
http://www.carbonite.com/  
http://aws.amazon.com/s3/  
http://en.wikipedia.org/wiki/Incremental_backup  
