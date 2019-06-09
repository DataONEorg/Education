<p align="center">
  <img width="250" src="https://www.nmepscor.org/sites/default/files/DataONE.png">
</p>   

# Contributing to the Data Management Skillbuilding Hub  
### Step One: Preparing Metadata Information    
---  
> **Items necessary for this step:**      
> - [x] a text file
> - [x] your organization's logo (.PNG only)
<details open>
<summary></summary>
<br>     

**The following information is needed when submitting educational materials to the data management hub:** 

- `title`: the title of your submission, as it will appear in the lists

- `layout`: is always ***bestpractice_cover***, ***lesson_cover***, or ***video_cover*** depending on which of the three you are submitting

- `tags`: a list of (short) keywords describing the content of the best practice text
  - Here is a [list](#tags) of currently existing tags used by DataONE

- `step`: a list of one or more steps of the data lifecycle to which this best practice applies.     
   -   The data life cycle and its steps can be found [here](https://www.dataone.org/data-life-cycle)

- `related`: ***(optional)*** a list of related best practices identifiers -- an identifier is the first three words of the title, separated by dashes.    
  -    A list of existing best practices can be found [here](https://www.dataone.org/all-best-practices)

- `update`: the date this best practice was created

- `author`: a list of authors that created the best practice

- `organization`: name of organization that oversaw the creation of the best practice

- `org_url`: website of the organization, organization logo will open this webpage when selected

- `org_logo`: name of the organization’s logo file ***(this must be a .png file).***

- `categories`: this must be listed as ***[“Best Practice”]***, ***["Teaching Module"]*** *if it is a lesson*, or ***["Video"]***    

**1. Copy the following text block and paste it into your empty text file**     
  ``` Example
---
title:
layout:
tags:
step:
related:
update:
author:
organization:
org_url:
org_logo:
categories:
---
```
**2. Fill out the appropriate information for each of the categories**     
- Here is an example that follows the proper formatting. ***Note that spaces, indents, lines, and dashes are actually very important here, so be sure to follow the formatting of the example as closely as possible!***
``` Example
---
title: Advertise your data using datacasting tools
layout: bestpractice_cover
tags:
 - access
 - data services
 - discover
step:
 - discover
related:
 - provide-a-citation
 - provide-identifier-for
 - recognize-stakeholders-in
update:
 - May 11, 2011
author: 
 - Cindy Parr
organization: DataONE
org_url: http://www.dataone.org
org_logo: DataONE.png
categories: ["Best Practice"]
---
```    
Keep the completed text file for later steps in the submission process.    

**3. Download a PNG file of your organizations logo and rename it appropriately.**    
The name for the PNG should match your input for `org_logo:`. For now the PNG will be saved on your desktop, but later we will upload it to a specific location in DataONE's GitHub repository.        
</details>     

### Step Two: Forking DataONE's Education Repository    
---     
> **Items necessary for this step:**     
> - [x] your own GitHub account online     
<details open>
<summary></summary>
<br>          

**1. Go to DataONEorg's Education repository**
  - https://github.com/DataONEorg/Education  
  
**2. Create your own fork of DataONEorg's Education repository**     
This means you will be creating a copy of the Education repository for your own use. Here, ***in your own fork***, you can change and edit without affecting the content of the original. Once you've perfected your changes, you can submit them for approval to the original repository.
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1_raB4dw8yL_Hfk0DakeVSbHwTeakUsEZ" align="center" height="" width="760" ></a>    

**3. In your fork, open up the the appropriate folder and click "Create New File"**  
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1pgl38ZoSvctoQF5C--ViaXNn9C2Yv9uL" align="center" height="" width="760" ></a>    
- If submitting a ***best practice:*** open the folder `"_bestpractices"`, and then open `"bestpractices"`, and create a new file here
- If submitting a ***lesson:*** open the folder `"_lessons"`, and then open `"lessons"`, and create a new file here
- If submitting a ***video:*** open the folder `"_videos"`, and then open `"videos"`, and create a new file here   

**4. Name your file**        
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1XN1deo0ZARkBrzsFPUcLMPqXjKZ_u0ju" align="center" height="" width="760" ></a>    
- If submitting a ***best practice:*** name your file for the first three words of the title, separated by dashes, and followed by the *.md* extension.     
- If submitting a ***lesson*** or a ***video***, name your file `index.md`     

**5. Copy and the metadata information from your text file and paste it here into the markdown (.md) file**
</details>    

### Step Three: Uploading your submission     
---     

Here is where you have to determine which category your submission falls under:     

- a `best practice` is a markdown document which is also transformed into a webpage such as [this one](https://www.dataone.org/best-practices/choose-and-use-standard-terminology-enable-discovery). ***Click [here](#bestpractice) if you are uploading a best practice.***     
- a `lesson` is a slideshow (optionally also comes with 'handouts' and 'exercises' in PDF) and is also transformed into a web page shown [here](https://www.dataone.org/education-modules). ***Click [here](#lesson) if you are uploading a lesson.***      
- a `video` is a video! ***Click [here](#video) if you are uploading a video.*** 
### <a name="bestpractice"></a>Uploading a Best Practice
### <a name="lesson"></a>Uploading a Teaching Module
### <a name="video"></a>Uploading a Video
### <a name="tags"></a>Existing Tags
---    
access, analyze, annotation, assure, backup, calibration, citation, coding, collect, controlled vocabulary, data archives, data consistency, data creators, data management plan, data model, data normalization, data processing, data quality, data services, data source, data sources, database, date, describe, disaster, recovery, discover, documentation, file, system, flag, format, geography, geospatial, image, integrate, location, measurement, metadata, missing, values, ontologies, parameter, plan, preserve, provenance, qualify, quality, replicable data, restore, standards, storage, tabular, taxonomy, terminology, time, units
