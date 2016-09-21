---
title: Protecting Your Data: Backups, Archives, & Data Preservation
author: DataONE Community Engagement & Outreach
update: Sept. 21, 2016
layout: slides
---

# Lesson Topics

- Key Digital Preservation Concepts
- Backups: Things to Consider
- Data Preservation
- Recommended Practices

???
These slides will cover several topics that relate to data protection.

The first section discusses the differences between three concepts: data protection, backups, and archiving, which are typically associated with digital preservation.  The second section will address why data protection is important. This will be followed by a section on things to consider when handling back-ups and how to deal with issues you may encounter.  The fourth section briefly discusses what data preservation is and what you should consider when dealing with it.  The last section discusses the importance of data backup plans along with recommended practices.


---

# Learning Objectives

After completing this lesson, the participant will be able to: 
- Define the differences between backups and archiving data
- Identify significant issues related to data backups
- Identify why backup plans are important and how they can fit into larger backup procedures
- Discuss what data preservation covers
- List several recommended practices

???
By the end of this presentation, you will be able to define the differences between data backups and archives, characterize issues that you might encounter during data backups, and lastly we’ll discuss recommended practices as related to backup plans.
Archives are used to preserve data for historical record and are intended to protect data integrity in case of disaster.

Suggested quiz questions:
Q1: How is archiving data different from backing up data?
Suggested answer: Data backup should occur throughout a research project, and backup files are created for use in the case of loss or corruption of the current version of the data. Archiving is usually only done for final versions of a data file, and archives are created with long-term storage in mind. 

Q2: Please describe at least two reasons why a researcher would choose to create data backups.
Suggested answers: 1) Creation of data backups limits or prevents loss of data in the case of accidental deletions, natural disasters, software bugs or hardware failures. 2) Data backups can also save time, money, and productivity by making it easier to respond to requests for data, allowing straightforward reproduction of results of past procedures based on older files. 3) Keeping data backups can also limit liability in cases of lawsuits or inability to reproduce data results

Q3: List at least four issues that should be considered when designing a data backup policy or system.
Suggested answers: 1) existing data backup policies (i.e., policies adopted by the project, office, department, organizational, funding source); 2) how often backups should be created and whether they should be full or partial backups; 3) media for backing up files (e.g., external disk, server, data repository); 4) locations where backups will be stored (including which locations and how many different locations); 5) metadata and organization/labeling systems necessary to retrieve desired backups efficiently; 6) whether backups will be manual or automatic; 7) quality control/quality assurance measures to check backup success and integrity of stored backup files; 8) who will be responsible for backups and serve as the contact person for users who need to retrieve backup files; 9) how outdated data will be disposed of; 10) plan for long-term storage including how long to keep backup files and what happens to backups after the project has ended; 11) designating person responsible for managing policies/workflow of backups, 12) incorporating existing legal requirements for storage and access over time. 

Q4: What are some good practices to follow when naming files?  Suggested answers: use consistent file names, use numbers or letters for file versioning, use file names that are descriptive and concise, avoid/rename generic file names


---
# The DataONE Data Life Cycle



???
In this lesson we will be focusing on data protection and backup which is associated with the categories assure and preserve in the data life cycle.  For definitions of the DataONE Data Life Cycle, see: dataone.org/data-life-cycle



---
# Data Protection, Backups, Archiving, Preservation:
Differences at a Glance
- Data Protection
  - Includes topics such as backups,  archives, and preservation; also includes physical security, encryption, and others not addressed here
    -More information about these topics can be found in the  “References” section
- Terms “backups” and “archives” are often used interchangeably, but do have different meanings
  - Backups: a copy (or copies) of the original file is made before the original is overwritten
  - Archives: preservation of the file
- Data Preservation
  - Includes archiving in addition to processes such as data rescue, data reformatting, data conversion, metadata

???
The terms data protection, data backups, data archiving, and data preservation are often used interchangeably but they do have different meanings and purposes.  Data protection  covers a wide variety of topics including backups, archives, preservation, physical security (such as the use of smart cards), encryption, and others including laws which govern data security.  However, these slides will not focus on this broader topic but rather will look specifically at backups, archives, and data preservation.

The terms data backups and data archiving are often used interchangeably as they both relate to saving a specific version of a file, but they do convey different processes.  The term “backup” is used specifically when making copies of various files with the knowledge that the files may change.  Backups are kept for a certain amount of time, but can be discarded after a specified time has passed.  Archiving is used when a file is to be preserved as-is, often at the end of a project and acts as a static (and usually final) record.

Data preservation encompasses many of these same methodologies, but can also include things like data rescue, reformatting of files, converting data, and the creation of metadata.  These first three topics will be discuss briefly in this lesson; however, metadata will be covered in another lesson.
---
# A Closer Look: Backups vs. Archiving
- Backups
  - Used to take periodic snapshots of data in case the current version is destroyed or lost
  - Backups are copies of files stored for short or near-long-term
  - Often performed on a somewhat frequent schedule
- Archiving
  - Used to preserve data for historical reference or potentially during disasters
  - Archives are usually the final version, stored for long-term, and generally not copied over
  - Often performed at the end of a project or during major milestones
- It is a good idea to have multiple copies of your backups and archives, in multiple places, in case one copy fails.

???
The main difference between data backups and archiving is that backups deal with data that is copied elsewhere and potentially can be overwritten again as the data changes.  Archiving makes a record of data that is usually in its final state.

For example, when a user performs a backup, they are in essence taking a snapshot of the data at that moment in time.  This allows the user to restore the file as needed, such as when the current version of the file is corrupted, lost, or somehow destroyed or altered.  Backups could also be used for short-term storage or near long-term storage, depending upon the user’s backup needs and procedures.  Backups are usually scheduled on a frequent basis.

Archiving deals more with records that could be used to create a historical snapshot of the data. This provides for preservation of the data for future needs.  Usually, archives are made when  a project ends, or when appropriate.

Regardless of whether you are dealing with backups or archives, you should have multiple copies in multiple places in case one (or many) versions fail.
---
# Why Perform Backups?
- Limit or negate loss of data, some of which may not be reproducible 
- Save time, money, productivity
- Help prepare for disasters
  - Accidental deletions
  - Fires, natural disasters
  - Software bugs, hardware failures
- Reproduce results of past procedures (if they were based on older files)
- Respond to data requests
- Limit liability

???
There are many reasons to perform backups including:
 - mitigate or prohibit the loss of data, which may or may not be reproducible
 - save time, money, and productivity as little to none of the data will have to be reproduced
 - having a backup already in place means you are prepared for when the unexpected happens, such as human error, disasters, or computer failures
 - allows you to go back to earlier versions and see what your results were.  For example, if you are creating models and used data from an earlier model run, the most recent file you have on your computer may not have the same data as when you first created the model output.
 - provides for the ability to send older files to others, regardless of the current version or state (for example, if the current version has been corrupted)
 - may allow you to respond during times when questioned results were based on older versions of files.  For example, you may find that you will have to justify your results in court or to other scientists.  By having access to older files, you may be able to respond to their requests for information.  Or, you may not be able to reproduce the data, and the original copy may be the only evidence of the data collection.
---
# Backups: Things to Consider
- What are the existing policies that might affect how and when you do data backups? 
  - May be separate project, office, department, funding source, or organizational polices
    - Policies may differ between groups; which has precedence?
  - Are backups already part of a larger data management or contingency plan for your group?
- Who is responsible for performing backups?
  - Users?  System administrators?  Both?
- Do these various policies fit your needs?

???
There are certain things to consider when creating backups, especially in the context of overall preservation strategies. 
For example: 
 - your office or project may have existing policies on when, where, and how  your backups can be performed.  They may already have a backup procedure in place that you can use or build upon.
Policies may differ among groups: for example, your office may perform backups once a month, but your project may need to have the data backed up more often
Policies between research groups may differ as to where the data backups live, and may have different restrictions on accessing the backups
For example: 
data backups are often a small part of a good and comprehensive data management plan during the project and overall data stewardship strategy.  Each data management plan should have specific guidelines on backups including when backups are performed, who is responsible for them, how the backups are accessed, where are they located.  By having the answers to these questions, you are better able to manage your data and know who is responsible for various components related to data backups.

Many offices already have backup systems in place, managed by IT staff.  But before you assume backups are being performed for you, you should confirm someone is responsible.  Even if there is a backup system available, it may only cover certain enterprise-wide systems (like servers), and not desktops.  And many offices have little or no IT staff, so performing backups may be solely up to you. 
You should identify and review the various policies (if available) and ensure they fit your needs and requirements.  If they don’t, you may need to discuss this with those involved in managing the backups or, establish your own schedule and plan.
You should identify and contact the person(s) in your institution or organization is responsible for overall data stewardship and data management planning. 
---
# Backups: Things to Consider; continued
- How often should you do backups to capture significant change?
  - Cost versus benefit
  - Continually? Daily? Weekly? Monthly?
- What kind of backups should you perform?
  - Partial: backing up only those files that have changed since the last backup
  - Full: backing-up all files
  - How often and what kind will depend upon what kind of data you have and how unique it is
- What about non-digital files (such as papers)?
  - Consider digitizing files

???
Other considerations include:
 - How often do you want to do backups?  The amount of time between backups depends on several things such as: can you afford to lose weeks worth of data if you only perform backups once a month?  If not, then you should consider doing them more often.  Are you creating real-time data that cannot be reproduced?  If so, you’ll want to consider continual backups.
 - You also need to consider the cost of doing backups versus the benefits.  If you are only occasionally working on a machine and the data isn’t that important, then you probably don’t need a top-of-the-line computer and backup software system which can run you thousands of dollars.  Alternatively, if you are creating files for a multi-million dollar project, you don’t want to be backing up your data by hand to an external drive.

There are different kinds of backups: partial ones that only back up the data that has changed since the last backup and full backups which backup everything.
Full backups are required when beginning to establish your backups.  They act as a full copy of all of your data.  Then, incremental (partial) backups can be performed which will then backup any data that has changed since the last backup performed.  Since you are only backing up a portion of your system, it is often quicker and requires fewer resources from your computer both in terms of processing and space.
It is still good to do full backups on a regular basis in case a previous full backup is inaccessible or unusable.  
Also, you do not want to overwrite the copies of your full backups.  If you were to overwrite a prior copy of a full backup, you may find that the newer copy doesn’t contain the same set of files as the older backup, or, the new file may be corrupted and then you are left without a viable full backup.

How often and what kind of backups you have depend upon how important your data is and what resources you have available.   

You should also think about how non-electronic files are backed up.  A disaster damages all files – not just electronic ones.
You may want to consider digitizing non-digital files so that they can be managed by an electronic backup system.  Make sure if you scan in the non-digital files that you scan them at a high DPI so that you do not lose any information.
Even if the information contained in a non-digital file (such as a field notebook) is entered into an electronic system, you may still want to scan in the paper copy so that the format and presentation of the original file is preserved.
---



