---
title: Contributing to Lessons
layout: generic
---
# Contributing a Best Practice to the Data Management Skillbuilding Hub  
###  Step One: Forking DataONEorg's Education Repository    
---  
> **Items necessary for this step:**      
> - [x] your own GitHub account online     

<details>
<summary>Instructions</summary>
<br>

<B>Forking a repository</B><br>
To submit content to the Skillbuilding Hub, you need to first <B>create a fork</B> of DataONEorg's Education repository. This means you will be creating <B><i>your own private copy</i></B> of the Education repository and storing it in your <B><i>GitHub account online</i></B>. Here, <i><B>in your fork</B></i>, you can edit and upload content <B><i>without affecting the original</i></B>.<br>

<br><B>The forking process will take a few minutes at most.</B> Once you've perfected your changes, you will later <B>merge</B> the changes you have made back into the original repository.<br><br>

<B>1.<a href="https://github.com/DataONEorg/Education" target="_blank" junk="_"> To start the forking process, go to DataONEorg's Education repository</a></B><br><br><br>

<B>2. In the right hand corner of DataONEorg's Education repository, click the "fork" button.</B>

<ul>
  <li>Make sure you are logged into your GitHub account before you press fork.</li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1KJ3kvkiB0WbixBEfN54GuGWhgLs-qYC6" align="center" height="" width="760" ></a>
<br><br>

<B>3. The forking process is complete!</B> Check "your repositories" in your account to make sure the Education repository was successfully forked.<br><br>

<B>4. Download a PNG file of your organization's logo onto your computer</B>
<ul>
  <li>If you are associated with a university, company, or other organization you must include their logo along with your submission.</li>
  <li>Once you have downloaded the logo, make sure to name the .PNG after your organization</li>
  <li><B><i>For now the PNG will be saved on your desktop, but later we will upload it to a specific location in DataONE's GitHub repository</i></B></li>
</ul>
</details>

### Step Two: Submittting the Best Practice
---   
> **Items necessary for this step:**     
> - [x]  a text file (e.g. a Word document, Notepad, Google Docs, any text editor, etc.)
> - [x]  your organization's logo (.PNG only)

<details open>
<summary>Instructions</summary>

<B>Creating the "frontmatter" file</B><br>

For every best practice submitted to the Skillbuilding Hub, the document must also have a front section containing metadata information about the best practice. This section of the best practice is also called the <B><i>"frontmatter"</i></B>.<br><br>

<p><b>The following metadata information is needed when submitting educational materials to the Data Management Skillbuilding Hub:</b></p>

<ul>
  <li><B>title:</B>The full title of your best practice</li>
  <li><B>layout:</B> is always <i><B>bestpractice_cover</B></i></li>
  <li><B>tags:</B> a list of (short) keywords describing the content of the best practice text</li>
    <ul>
      <li>Click <a href="#tags">here</a> for a list of currently existing tags</li>
    </ul>  
  <li><B>step:</B> a list of one or more steps of the data lifecycle to which this best practice applies.</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/blob/master/_lessons/lessons/02_datasharing/02_datasharing.pdf" target="_blank junk=_">Here's a slideshow explaining the data lifecycle.</a></li>
    </ul>
  <li><B>related:</B> <i><B>(optional)</B></i> Choose one or a few best practices that are related to yours. List their identifier -- an identifier is the first three words of the title, separated by dashes.</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/tree/master/_bestpractices/bestpractices" target="_blank junk=_">List of existing Best Practices</a></li>
    </ul>
  <li><B>update:</B> the date this best practice was created</li>
  <li><B>author:</B> a list of authors that created the best practice</li>
  <li><B>organization:</B> name of organization that oversaw the creation of the best practice</li>
  <li><B>org_url:</B> website of the organization, organization logo will open this webpage when selected</li>
  <li><B>org_logo:</B> name of the organization’s logo file <i><B>(this must be a .png file).</B></i></li>
  <li><B>categories:</B> this must be listed as <i><B>[“Best Practice”]</B></i></li>
</ul>

<b>1. Copy the following text block and paste it into your empty text file</b>    
<pre>
  <code>
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
  </code>
</pre>

<B>2. Fill out the appropriate information for each of the categories</B>

<ul>
<li>Here is an example that follows the proper formatting. <B><i>Note that spaces, indents, lines, and dashes are actually very important here, so be sure to follow the formatting of the example as closely as possible!</i></B></li>
</ul>

<pre>
  <code>
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
  </code>
</pre>

Now your frontmatter information is completed. <B><i>Save your text file</i></B>, and we will copy and paste this text at a later step in the submission process.<br><br>

<B>3. Creating your best practice document </B> In your fork, open up the the appropriate folder and click <B>"Create New File."</B><br>

<ul>
  <li>Go to <i>`(yourGitHubAccount)/Education/_bestpractices/bestpractices`</i> and click <B>Create New File</B>, located in the upper right-hand corner</li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1jZoNdFphcUKkZjeapXBaSOY1XqxYsaLL" align="center" height="" width="760" ></a><br>

<B>4. Name your file</B><br>      
Name your file for the first three words of the title, separated by dashes, and followed by the <i>.md</i> extension.<br>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1nqZEBbS3ExggE45a08CevTBZDGEsLxno" align="center" height="" width="760" ></a><br>

<B>5. Copy the "frontmatter" saved in your text file from Step One and paste it here into the markdown (.md) file</B>
  <ul>
    <li><i>Be sure to include the three dashes at the beginning and end of the section</i></li>
  </ul><br>

<B>6. Add the content of your best practice directly into your markdown file</B>
<ul>
  <li>You will be putting your content immediately after the three dashes "---"</li>
  <li>The format for the content of a best practice should be as follows:</li><br>
    <B><ol>
      <li>A description of the best practice</li>
      <li>Description Rationale</li>
      <li>Additional Information</li>
      <li>Examples</li>
    </ol></B>
  </ul>

<B>7. Commit your Changes</B>
<ul>
  <li>Scroll to the bottom of your markdown document to commit your changes</li>
  <li><B><i>Committing</i></B> will submit the markdown file to <B><i>your</i></B> fork of the Education repository</li>
</ul>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1iWHzkS8vBX8svyqwiMG50K093eWCUx9y" align="center" height="" width="760" ></a><br>

<B>8. Uploading your organization's logo</B>

<ul>
  <li>Go to <i>`(yourGitHubAccount)/Education/_bestpractices/bestpractices/logos`</i> in your fork of the Education repository.</li>
  <li>Click on "Upload Files" and drag your logo here.</li>
  <li>Commit your change</li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1titY7LpTJ5BLeG8OMF-V7eU2cKVHk3jd" align="center" height="" width="760" ></a><br><br>

<B>9. <i>[Optional Step]</i> Adding images</B>
<ul>
    <li>If your best practice includes images in it, you must upload them to <B><i>your fork</i></B> of the Education Repository.</li>
    <li>Go to <i>`(yourGitHubAccount)/Education/_bestpractices/bestpractices/images`</i> in your fork</li>
    <li>Upload your image to the <i>"images"</i> folder, and give each image a unique identifier.</li>
      <ul>
        <li><i>An image name should begin with it's best practice identifier, followed by an underscore and a word that describes the image itself</i></li>
        <li><i>Images can be .JPG or .PNG</i></li>
      </ul>
    <li>Once all the images are uploaded, commit your change.</li>
  </ul>
</details>

### Step Three: Creating a Pull Request
---
***Creating a pull request*** means that you are requesting the original repository to *"pull"* or accept all the changes you just made.

<ul>
  <li><i>Do not complete this step until <B>all</B> of the materials necessary for your submission have already been uploaded to GitHub!</i></li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1LEJnnxkd2Ds8oOZPpbjUxQNqF3h1NjSl" align="center" height="" width="760" ></a>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1lmQpXfFXSgGT7M4_mbz4U73E44KdNwqD" align="center" height="" width="760" ></a><br>

<B>That's it! You have completed all the steps.</B> Once someone has approved your pull request, you will be able to find your submission in DataONE's repository.
<br><br>

### How is the Data Management Skillbuilding Hub website created?
---
The educational resources that exist in DataONE's GitHub repository are rendered into the Data Management Skillbuilding Hub webpage using Jekyll. When sharing presentations, slides themselves are rendered using remarkjs. The rendering is done using GitHub pages, which builds the site from the master branch. You can build the site locally with jekyll serve -w, and it will be available at http://localhost:4000 for you to review.

The stylesheets are defined in resources/styles, and rendered to resources/dataone.css using lessc (just type make from the root).

### <a name="tags"></a>Existing Tags
---    
access, analyze, annotation, assure, backup, calibration, citation, coding, collect, controlled vocabulary, data archives, data consistency, data creators, data management plan, data model, data normalization, data processing, data quality, data services, data source, data sources, database, date, describe, disaster, recovery, discover, documentation, file, system, flag, format, geography, geospatial, image, integrate, location, measurement, metadata, missing, values, ontologies, parameter, plan, preserve, provenance, qualify, quality, replicable data, restore, standards, storage, tabular, taxonomy, terminology, time, units
