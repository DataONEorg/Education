---
title: Intro to Data Management
update: Sept. 20, 2016
layout: slides
permalink: /introduction-data-management
---


# Why Data Management?

 ![CC image by University of Maryland Press Releases on Flickr](intro-data-management/images/slide-1-intro.jpg)


???
No notes are available for this slide.

---

# Lesson Topics

* The data world around us
* Importance of data management
* The data lifecycle
* The case for data management

![Image Caption Here](intro-data-management/images/lesson-topics.png)

???
The topics covered in this module will answer the questions:

---

# Learning Objectives

* Give two general examples of why increasing amounts of data is a concern
* Explain, using two examples, how lack of data management makes an impact
* Define the research data lifecycle
* Give one example of how well-managed data can result in new scientific conclusions

---

# Data Realities

---

 ![Magazines](intro-data-management/images/Slide05.jpg)

???
The world today is filled with science news, from climate change to hurricanes – and it all affects the people inhabiting the earth.

---
## Data Deluge

Data are collected from sensors, sensor networks, remote sensing, observations,
and more -  this calls for increased attention to data management and stewardship.

 ![caption here](intro-data-management/images/data-deluge.jpg)

???
Data are being generated in massive quantities daily. Improvements in technology enable higher precision and coverage in data acquisition and makes higher capacity systems store and migrate more data –increasing the importance of managing, integrating, and re-using data.

---

## A World of Data Around Us

![Source: John Gantz, IDC Corporation: The Expanding Digital Universe](intro-data-management/images/data-around-us.png)

**there are two graphics on this slide -- need to fix this**
???
The amount of available storage is not keeping up with the amount of data flooding in daily. How do we decide what data we keep?

---
# Data Loss Can Be Caused by
**NOTE: LEAH SPLIT THIS INTO 2 slides. It's a very long list. IS THIS OK AS RENDERED?**

* Natural disaster
* Facilities infrastructure failure
* Server hardware/software failure
* Application software failure
* External dependencies (e.g. PKI failure)
* Format obsolescence

![CC image by momboleum on Flickr](intro-data-management/images/building-fire.png)
---

# Data Loss Can Be Caused by

* Legal encumbrance
* Human error
* Malicious attack by human or automated agents
* Loss of staffing competencies
* Loss of institutional commitment
* Loss of financial stability
* Changes in user expectations and requirements

![CC image by Sharyn Morrow on Flickr](intro-data-management/images/data-loss.jpg)

---

# Poor Data Management Affects Everyone

**MEDICARE PAYMENT ERRORS NEAR $20B” (CNN) December 2004**
> “MEDICARE PAYMENT ERRORS NEAR $20B” (CNN) December 2004
     Miscoding and Billing Errors from Doctors and Hospitals totaled $20,000,000,000 in FY
     2003    (9.3% error rate) . The error rate measured claims that were paid despite being
     medically unnecessary, inadequately documented or improperly coded. In some
     instances, Medicare asked health care providers for medical records to back up their
     claims and got no response.  The survey did not document instances of alleged fraud.    
    This error rate actually was an improvement over the previous fiscal year (9.8% error rate)."

![CC image by Sharyn Morrow on Flickr](intro-data-management/images/error.png)

---

# Poor Data Management Affects Everyone
**LEAH SPLIT THIS INTO 3 SLIDES -- do you want the slide notes to be the same for all 3?**

**AUDIT: JUSTICE STATS ON ANTI-TERROR CASES FLAWED” (AP) February 2007**
> The Justice Department Inspector General found only two sets of data out of 26  
> concerning terrorism attacks were accurate. The Inspector General said the data “appear to be
> the result of decentralized and haphazard methods of collections … and do not appear
> to be intentional.”

![CC image by Sharyn Morrow on Flickr](intro-data-management/images/error.png)

???
Note:
Data Costs

Consider some of the data management issues that made headlines, affecting agencies and organizations.  Data quality is not limited to any one organization.  These examples show costs (in terms of money lost) due to a lack of data quality control.
---

# Poor Data Management Affects Everyone

**OOPS! TECH ERROR WIPES OUT Alaska Info” (AP) March 2007**
> A technician managed to delete the data and backup for the $38 billion Alaska oil   
> revenue fund – money received by residents of the State. Correcting the errors cost the
> State an additional $220,700.

![CC image by Sharyn Morrow on Flickr](intro-data-management/images/error.png)

---

# Poor Data Management Example - Science

**NOTE: THE NOTES ON THIS SLIDE ARE THE SAME AS THE SLIDE - PROBABLY NOT IDEAL**

A wildlife biologist for a small field office provided support for staff GIS needs.
The data were stored on her workstation. When the biologist relocated to another
office, no one understood how the data was stored or managed.

**Solution:** A state office GIS specialist retrieved the workstation and sifted through files trying to salvage relevant data.

**Cost:** 1 work month ($4,000) plus the value of
    data that was not recovered


> Consider that the situation could have been worse, because the data was not
being backed up as it would have been if stored on a server.

???
A wildlife biologist for a small field office was the in-house GIS expert and provided support for all the staff’s GIS needs.  However, the data was stored on her own workstation.  When the biologist relocated to another office, no one understood how the data was stored or managed.

The solution: A state office GIS specialist retrieved the workstation and sifted through files trying to salvage relevant data.

The cost:  1 work month ($4,000) plus the value of data that was not recovered.

Consider that this situation could have been much worse because the data was not being backed up as it would have been if stored on a server.

---
## Poor Data Management Example - Federal Agency

In preparation for a Resource Management Plan, an office discovered 14 duplicate GPS inventories of roads.  However, because none of the inventories had enough metadata, it was impossible to know which inventory was best or if any of the inventories actually met their requirements.

**Solution:** Re-Inventory roads

**Cost:** Estimated 9 work months/inventory
          @$4,000/wm
          (14 inventories = $504,000)

![CC image by ruffin_ready on Flickr](intro-data-management/images/data-mgt-ex.png)
---

## Importance of Data Management

> Please forgive my paranoia about protocols, standards, and data review.  I'm
in the latter stages of a long career with USGS (30 years, and counting), and h
ave experienced much.  Experience is the knowledge you get just after you needed
it.

> Several times, I've seen colleagues called to court in order to testify about
conditions they have observed.  

>Without a strong tradition of constant review and approval of basic data, they
would've been in deep trouble under cross-examination.  Instead, they were able
to produce field notes, data approval records, and the like, to back up their
testimony.  

> It's one thing to be questioned by a college student who is working on a project
for school. *It's another entirely to be grilled by an attorney under oath with
the media present.*”

> *- Nelson Williams, Scientist U.S. Geological Survey*

---

# Importance of Data Management

The climate scientists at the centre of a media storm over leaked emails were
yesterday cleared of accusations that they fudged their results and silenced
critics, but a review found they had **failed to be open enough about their work**.

![](intro-data-management/images/guardian.png)

---
# Why Manage Data: Researcher Perspective
**NOTE: the notes here are also identical to the slide content**

Manage your data for yourself:

* Keep yourself organized – be able to find your files (data inputs, analytic scripts, outputs at various stages of the analytic process, etc)
* Track your science processes for reproducibility – be able to match up your outputs with exact inputs and transformations that produced them
* Better control versions of data – identify easily versions that can be periodically purged
* Quality control your data more efficiently


???
Manage your data for yourself:
Keep yourself organized – be able to find your files (data inputs, analytic scripts, outputs at various stages of the analytic process, etc)
Track your science processes for reproducibility – be able to match up your outputs with exact inputs and transformations that produced them
Better control versions of data – identify easily versions that can be periodically purged
Quality control your data more efficiently

---

# Why Data Management: Researcher Perspective

**NOTE: SLIDES NOTES IDENTICAL TO SLIDE**

* Make backups to avoid data loss
* Format your data for re-use (by yourself or others)
* Be prepared: Document your data for your own recollection, accountability, and re-use (by yourself or others)
* Prepare it to share it – gain credibility and recognition for your science efforts!

![CC image by UWW ResNet on Flickr](intro-data-management/images/master-backup.png)

---

# Why Data Management: Foundation to Advance Science

**NOTES ARE IDENTICAL TO SLIDES**
* Data is a valuable asset – it is expensive and time consuming to collect
* Data should be managed to:
  * Maximize the effective use and value of data and information assets
  * Continually improve the quality including: data accuracy, integrity, integration,
  timeliness of data capture and presentation, relevance and usefulness
  * Ensure appropriate use of data and information
  * Facilitate data sharing
  * Ensure sustainability and accessibility in long term for re-use in science

---

# Data Management Facilitates Sharing and Re-Use

![](intro-data-management/images/data-mgt-graphic.png)

???
Data management and organization facilitate archiving, sharing and publishing
data. These activities feed data re-use and reproducibility in science.

---

# Well-Managed Data Can Result in Re-use, Integration and New Science

**NOTE: THE GRAPHIC ON THIS SLIDE IS COMPLEX - DOES IT NEED TO BE?**

![](intro-data-management/images/data-integration.png)

???
By re-using data collected from a variety of sources – eBird database, land cover data, meteorology, and remotely sensed -- this project was able to compile and process the data using supercomputering to determine bird migration routes for particular species.


---
# Data Integration

**NOTE:  THERE ARE SEVERAL IMAGES HERE BUT ONLY ONE HAS A CITATION.**
![Images  courtesy of Cornell Ornithology Lab](intro-data-management/images/data-integration2.png)


---
# Where a majority of data end up now…


![](intro-data-management/images/where-data-end.png)
???
There is an abundance of data and metadata (if it is done) end up in filing cabinets, on discarded hard drives, in hard-copy journals on the library shelves -- or on the web, but many are subscription only journals.


---
# Imagine if data were more accessible….

![](intro-data-management/images/data-more-accessible.png)

???
Data should be properly managed and eventually be placed where they are accessible,
understandable, and re-usable.

---

# Why Well managed, publically accessible data are important
**NOTE: NOTES ARE THE SAME AS THE SLIDES**

* Increases the impact and visibility of research
* Promotes innovation and potential new data uses
* Leads to new collaborations between data users and creators
* Maximizes transparency and accountability
* Enables scrutiny of research findings
* Encourages improvement and validation of research methods
* Reduces cost of duplicating data collection
* Provides important resources for education and training

-- Adapted from the UK Data Archive

---

# New Discoveries

A new image processing technique reveals something not before seen in this Hubble Space Telescope image taken 11 years ago: A faint planet (arrows), the outermost of three discovered with ground-based telescopes last year around the young star HR 8799.D. Lafrenière et al., Astrophysical Journal Letters

![D. Lafrenière et al., ApJ Letters](intro-data-management/images/hubble.png)

---

# New Discoveries

![D. Lafrenière et al., ApJ Letters](intro-data-management/images/hubble.png)

“The first thing it tells you is how valuable maintaining long-term archives can be. Here is a major discovery that’s been lurking in the data for about 10 years!” comments Matt Mountain, director of the Space Telescope Science Institute in Baltimore, which operates Hubble.


“The second thing its tells you is having a well calibrated archive is necessary but not sufficient to make breakthroughs — it also takes a very innovative group of people to develop very smart extraction routines that can get rid of all the artifacts to reveal the planet hidden under all that telescope and detector structure.”


---

# What is the Data Life Cycle?

![](intro-data-management/images/data-life-cycle.png)

???
A data lifecycle illustrates stages thru which well-managed data passes from the inception of a research project to its conclusion. In the reality of science research, the stages do not always follow a continuous circle.


---

# For Each Stage of the Data Lifecycle…

**NOTES ARE IDENTICAL TO SLIDE TEXT**

* …there are best practices…..and….tools to help!
* The following data management lessons will illustrate in detail each stage of the data lifecycle
* Your well-managed and accessible data can contribute to science in ways you may not even imagine today!


---

# Summary

* The data deluge has created a surge of information that needs to be well-managed and made accessible.
* The cost of not doing data management can be very high.
* Be cognizant of best practices and tools associated with the data lifecycle to manage your data well.
* Many benefits are associated with the act of managing data, including the ability to find, access, understand, integrate and re-use data.

---

# Summary

If data are:

* Well-organized
* Documented
* Preserved
* Accessible
* Verified as to Accuracy and validity

Result is:

* High quality data
* Easy to share and re-use in science
* Citation and credibility to the researcher
* Cost-savings to science

???
For each stage of the data lifecycle…there are best practices…..and….tools to help!

The following data management lessons will illustrate in detail each stage of the data lifecycle

Your well-managed and accessible data can contribute to science in ways you may not even imagine today!


---

# Resources

1. Bureau of Land Management. Data Management Training Workshop (2011)
1. Strasser, Carly, PhD. Data Management for Scientists, February 2012
1. UK Data Archive. Managing and Sharing Data: Best Practices for Researchers, May 2011
1. DAMA International, The DAMA Guide to the Data Management Body of Knowledge


---
# Summary

Download Slides: http://www.dataone.org/education-modules

Suggested citation:
DataONE Education Module: Data Management. DataONE. Retrieved Nov12, 2012. From http://www.dataone.org/sites/all/documents/L01_DataManagement.pptx

**Copyright license information:**
No rights reserved; you may enhance and reuse for your own purposes. Please
provide appropriate citation and attribution to DataONE.

![](intro-data-management/images/cc-0.png)
