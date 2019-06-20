---
title: Contributing to Lessons
layout: generic
---
# Contributing to the Data Management Skillbuilding Hub  
###  Step One: Forking DataONE's Education Repository    
---  
> **Items necessary for this step:**      
> - [x] your own GitHub account online     

<details open>
<summary>Instructions</summary>

<B>1. Go to DataONEorg's Education repository</B>
<ul>
  <li>Click <a href="https://github.com/DataONEorg/Education">here</a> to go to DataONE's Education Repository</li>
</ul><br>

<B>2. Create your own fork of DataONEorg's Education repository</B><br>
This means you will be creating a copy of the Education repository for your own use. Here, <i><B>in your own fork</B></i>, you can change and edit without affecting the content of the original. Once you've perfected your changes, you can submit them for approval to the original repository.<br><br>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1KJ3kvkiB0WbixBEfN54GuGWhgLs-qYC6" align="center" height="" width="760" ></a>
<br><br>

<B>3. Download a PNG file of your organization's logo</B>
<ul>
  <li>If you are associated with a university, company, or other organization you must include their logo along with your submission.</li>
  <li>Once you have downloadeed it, make sure to name the .PNG after your organization</li>
  <li>For now the PNG will be saved on your desktop, but later we will upload it to a specific location in DataONE's GitHub repository</li>
</ul>
</details>

### Step Two: Uploading your Educational Materials    
---     

Here is where you have to determine which category your submission falls under:     
<ol>
  <li> a <B>best practice</B> is a markdown document containing a description and examples of the best practice. Current best practices can be seen <a href="https://www.dataone.org/best-practices/all-best-practices">here</a></li>
    <ul>
      <li><i><B>Click <a href="#bestpractice">here</a> if you are uploading a best practice.</B></i></li>
    </ul>
  <li> a <B>lesson</B>
  can come in a variety of formats. Oftentimes, lessons are contributed as <B>slideshows</B></li>
  <ul>
    <li>There are two types of slideshows you can contribute: <B>a slideshow PDF</B> OR a <B>slideshow in Markdown</B></li>
	  <li>Contributing a <B> slideshow PDF</B> would mean that you simply upload your file into the repository. Users will have to download your PDF in order to view it.</li>
	  <li>Contributing a <B>Markdown slideshow</B> would take a little more work because you would have to format and write your lesson in Markdown. <B>HOWEVER</B>, Markdown is an <i>extremely lightweight, easy-to-read, easy-to-write, and easy-to-learn</i> language! <a href="https://github.com/saraneh/Education/blob/master/_lessons/lessons/00_markdown">HERE</a> is a quick and straightforward resource on creating a lesson in Markdown.</li>
		<ul>
      <li>creating a Markdown slideshow allows viewers to play the slideshow directly from the webpage. No downloading necessary!</li>
    </ul>
  <li> Lessons can also come with supplementary materials, such as the following:</li>
    <ul>
      <li><B>handouts</B> = a single document containing text and graphics</li>
	    <li><B>exercises</B> = a single document containing text and graphics and example problems</li>
	    <li><B>supplementary data</B>= data files to be used in conjunction with exercises</li>
    </ul>
  <li> In order your submission to be considered as a lesson, you have to contribute either a slideshow, a handout, or an exercise, or a combination of these things.</li>
  <li><i><B>Click <a href="#lesson">here</a> if you are uploading a lesson</B></i></li>
  </ul>
  <li> a <B>video</B> is a video!</li>
  <ul>
    <li><i><B>Click <a href="#video">here</a> if you are uploading a video</B></i></li>
  </ul>
</ol>

### <a name="bestpractice"></a>Uploading a Best Practice
---   
> **Items necessary for this step:**     
> - [x]  a text file (e.g. a Word document, Notepad, Google Docs, any text editor, etc.)
> - [x]  your organization's logo (.PNG only)

<details>
<summary>Instructions</summary>
<p><b>The following information is needed when submitting educational materials to the data management hub:</b></p>

<ul>
  <li><B>title:</B>The full title of your best practice</li>
  <li><B>layout:</B> is always <i><B>bestpractice_cover</B></i></li>
  <li><B>tags:</B> a list of (short) keywords describing the content of the best practice text</li>
    <ul>
      <li>Click <a href="#tags">here</a> for a list of currently existing tags</li>
    </ul>  
  <li><B>step:</B> a list of one or more steps of the data lifecycle to which this best practice applies.</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/blob/master/_lessons/lessons/02_datasharing/02_datasharing.pdf">Here's a slideshow explaining the data lifecycle.</a></li>
    </ul>
  <li><B>related:</B> <i><B>(optional)</B></i> Choose one or a few best practices that are related to yours. List their identifier -- an identifier is the first three words of the title, separated by dashes.</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/tree/master/_bestpractices/bestpractices">List of existing Best Practices</a></li>
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

Keep the completed text file for later steps in the submission process.<br><br>

<B>3. In your fork, open up the the appropriate folder and click "Create New File":</B><br>
<ul>
  <li>Go to <B><i>Education\_bestpractices\bestpractices</i></B> and create a new file here.</li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1jZoNdFphcUKkZjeapXBaSOY1XqxYsaLL" align="center" height="" width="760" ></a><br>

<B>4. Name your file</B><br>      
Name your file for the first three words of the title, separated by dashes, and followed by the <i>.md</i> extension.<br>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1nqZEBbS3ExggE45a08CevTBZDGEsLxno" align="center" height="" width="760" ></a><br>

<B> 5. Copy and paste the metadata information from your text file and paste it here into the markdown (.md) file</B><br><br>

<B>6. Add the content of your best practice directly into your markdown file</B>
<ul>
  <li>You will be putting your content immediately after the three dashes "---" at the end of the metadata section <i>(also known as "frontmatter").</i></li>
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
  <li>Go to <B><i>Education\_bestpractices\bestpractices\logos</i></B> in your fork of the Education repository.</li>
  <li>Click on "Upload Files" and drag your logo here.</li>
  <li>Commit your change</li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1titY7LpTJ5BLeG8OMF-V7eU2cKVHk3jd" align="center" height="" width="760" ></a><br><br>

<B>9. <i>[Optional Step]</i> Adding images</B>
<ul>
    <li>If your best practice includes images in it, you must upload them to <B><i>your fork</i></B> of GitHub's Education Repository.</li>
    <li>Go to <i><B>Education\_bestpractices\bestpractices\images</B></i> in your fork</li>
    <li>Upload your image to the <i>"images"</i> folder, and give each image a unique identifier.</li>
      <ul>
        <li><i>An image name should begin with it's best practice identifier, followed by an underscore and a word that describes the image itself</i></li>
        <li><i>Images can be .JPG or .PNG</i></li>
      </ul>
    <li>Once all the images are uploaded, commit your change.</li>
  </ul>

<B>10. Create a pull request</B>
<ul>
  <li>Last step!!! <a href="#pullrequest">Click here</a> to see the instructions on how to create a pull request.</li>
</ul>
</details>

### <a name="lesson"></a>Uploading a Lesson
---
> **Items necessary for this step:**     
> - [x]  a text file (e.g. a Word document, Notepad, Google Docs, any text editor, etc.)
> - [x]  your organization's logo (.PNG only)
> - [x] your lesson, and any additional files

<details>
<summary>Instructions</summary><br>
<p><b>The following information is needed when submitting educational materials to the data management hub:</b></p>
<ul>
  <li><B>title:</B>The full title of your lesson</li>
  <li><B>author:</B> a list of authors that created the lesson</li>
  <li><B>organization:</B> name of organization that oversaw the creation of the lesson</li>
  <li><B>org_url:</B> website of the organization, organization logo will open this webpage when selected</li>
  <li><B>org_logo:</B> name of the organization’s logo file <i><B>(this must be a .png file).</B></i></li>
  <li><B>update:</B> the date this lesson was created</li>
  <li><B>layout:</B> is always <i><B>lesson_cover</B></i> for all lessons</li>
  <li><B>status:</B></li>
  <li><B>tags:</B> a list of (short) keywords describing the content of the best practice text</li>
    <ul>
      <li>Click <a href="#tags">here</a> for a list of currently existing tags</li>
    </ul>
  <li><B>categories:</B> this must be listed as <i><B>["Teaching Module"]</B></i></li>
  <li><B>previous lesson:</B></li>
  <li><B>next lesson:</B></li>
  <li><B>handout:</B> <i>[Optional]</i> If you have a handout to contribute, paste the exact name of the handout here as well as its extension</li>
  <li><B>powerpoint:</B> The exact name of your powerpoint followed by its extension</li>
  <li><B>exercise:</B> <i>[Optional] </i>If you have an exercise to contribute, paste the exact name of the exercise here as well as its extension</li>
</ul>

<b>1. Copy the following text block and paste it into your empty text file</b>    
<pre>
  <code>
  ---
  title:
  author:
  organization:
  org_url:
  org_logo:
  update:
  layout:
  status:
  tags:
  categories:
  prevlesson:
  nextlesson:
  handout:
  ppt:
  exercise:
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
  title: "Why data management?"
  author: "DataONE Community Engagement & Outreach Working Group"
  organization: DataONE
  org_url: http://www.dataone.org
  org_logo: DataONE.png
  update: Sept. 20, 2016
  layout: lesson_cover
  status: published
  tags: ["Data Management", Plan]
  categories: ["Teaching Module" ]
  prevlesson: 02_datasharing
  nextlesson: 04_entry
  handout: L03_DataManagement_Handout.pdf
  ppt: L03_DataManagementPlanning.pptx
  exercise: L03_Exercise.pdf
  ---
  </code>
</pre>

<B>3. Create a folder for your files</B><br>
With a lesson, you will have to submit multiple items. Consequently, you must first make a folder to contain everything!
<ul>
  <li><B>The folder naming convention is as follows:</B> <i>(a number) _ (the name of your lesson)</i></li>
    <ul>
      <li>The number at the beginning should be the next one in the sequence according to the number of lessons that already exist in the repository. <a href="https://github.com/DataONEorg/Education/tree/master/_lessons/lessons">Click here to see the current list of lessons.</a></li>
    </ul>
  <li>In your fork, go to <B>Education\_lessons\lessons</B> and click <B>"Create New File"</B></li>
  <li>Type the name of your folder followed by <B>a slash "/"</B></li>
    <ul>
      <li>A new folder will automatically be created. Now create a file called <B><i>"index.md"</i></B></li>
    </ul>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1YUdOwtm0FK6z0WqFVjlHLYk_DhHAdfDa" align="center" height="" width="760" ></a><br>  

<B>5. Copy and paste the metadata information from your text file and paste it here into the markdown (.md) file</B>
  <ul>
    <li>This section <i>(delineated by the three dashes: "---")</i> is what we call the <B><i>frontmatter</i></B>.</li>
  </ul>

<B>6. Add a brief summary of your lesson</B>
<ul>
  <li>After the <B><i>frontmatter</i></B> section, simply provide a brief explanation of what problem your lesson is addressing and what methods it proposes for solving it.</li>
</ul>

<B>7. Commit your Changes</B>
<ul>
  <li>Scroll to the bottom of your markdown document to commit your changes</li>
  <li><B><i>Committing</i></B> will submit the markdown file to <B><i>your</i></B> fork of the Education repository</li>
</ul>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1iWHzkS8vBX8svyqwiMG50K093eWCUx9y" align="center" height="" width="760" ></a><br>

<B>8. Add your lesson and other files to your lesson folder</B>
<ul>
  <li>Go to your lesson folder, and click <B><i>"Upload Files"</i></B>. Then just drag and drop your powerpoint, as well as any exercises or handouts that you have to contribute!</li>
</ul>

<B>9. Uploading your organization's logo</B>
<ul>
  <li>Go to <i><B>Education\_lessons\lessons\logos</B></i> in your fork of the Education repository.</li>
  <li>Click on "Upload Files" and drag your logo here.</li>
  <li>Commit your change</li>
</ul>

<B>10. Create a pull request</B>
<ul>
  <li>Last step!!! <a href="#pullrequest">Click here</a> to see the instructions on how to create a pull request.</li>
</ul>

</details>


### <a name="video"></a>Uploading a Video
---
> **Items necessary for this step:**     
> - [x]  a text file (e.g. a Word document, Notepad, Google Docs, any text editor, etc.)
> - [x]  your organization's logo (.PNG only)
> - [x] the embed link for your video

<details>
<summary>Instructions</summary><br>
<p><b>The following information is needed when submitting educational materials to the data management hub:</b></p>
<ul>
  <li><B>title:</B>The full title of your lesson</li>
  <li><B>layout:</B> is always <i><B>video_cover</B></i></li>
  <li><B>tags:</B> a list of (short) keywords describing the content of the best practice text</li>
    <ul>
      <li>Click <a href="#tags">here</a> for a list of currently existing tags</li>
    </ul>
  <li><B>step:</B> a list of one or more steps of the data lifecycle to which this best practice applies.</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/blob/master/_lessons/lessons/02_datasharing/02_datasharing.pdf">Here's a slideshow explaining the data lifecycle.</a></li>
    </ul>
  <li><B>related:</B> <i><B>(optional)</B></i> Choose one or a few other videos in the DataONE repository that are related to yours. List the folder name of the video</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/tree/master/_videos/videos">List of existing videos</a></li>
    </ul>
  <li><B>update:</B> the date this lesson was created</li>
  <li><B>author:</B> a list of authors that created the lesson</li>
  <li><B>video_embedurl:</B></li>
  <li><B>organization:</B> name of organization that oversaw the creation of the lesson</li>
  <li><B>org_url:</B> website of the organization, organization logo will open this webpage when selected</li>
  <li><B>org_logo:</B> name of the organization’s logo file <i><B>(this must be a .png file).</B></i></li>
  <li><B>categories:</B> this must be listed as <i><B>["Video"]</B></i></li>

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
  video_embedurl:
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
  title: Example video for the data management hub
  layout: video_cover
  tags:
    - example
    - help
  step:
    - describe
    - discover
  related:
    - similar-video-to
  update:
    - August 14, 2018
  author:
    - Megan Mach
  video_embedurl: https://player.vimeo.com/video/106484168
  organization: DataONE
  org_url: http://www.dataone.org
  org_logo: DataONE.png
  resource: true
  categories: ["Video"]
  ---
  </code>
</pre>

<B>3. Getting the Embed Link for your Video</B>
<ul>
  <li>When embedding a video into a webpage, there's a specific link that is needed</li>
  <li>To find that link, go to your video. When you click <B>"Share"</B>, there is an option that says <i>"Embed"</i> or <i>"Copy Embed Link"</i></li>
    <ul>
      <li>Other times, the embed link can be found when clicking on a video's <B>"Options"</B>. For example, on Facebook the embed option is found when you click the &nbsp; <B>...</B> &nbsp; symbol on a video</li>
    </ul>
  <li>This code allows you to display a video on your own webpage. However, you do not need the complete code. You only need a snippet of this code, called the <B>SRC.</B></li>
    <ul>
      <li>You can find the SRC because it is always near the beginning of the code and is labeled with <B>src="____"</B></li>
      <li>Copy everything that occurs <i>after</i> <B>src="</B> <i>up until</i> the <B>first right pointing arrow you encounter ( > )</B></li>
    </ul>
  <li>This portion of the code that you just copied is what you will paste next to <B>video_embedurl:</B> in the metadata section above.</li>
  </ul>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1eufRbGbD3OrM-3uPlb0Pag5KuhzTsByO" align="center" height="" width="760" ></a><br><br>

<B>4. Create a folder for your files</B><br>
With a video, you will have to create folder in your fork as well as a markdown file to go inside of it.
<ul>
  <li>The folder should be named after the first three words of your video title, separated by dashes</li>
  <li>In your fork, go to <B>Education\_videos\videos</B> and click <B>"Create New File"</B></li>
  <li>Type the name of your folder followed by <B>a slash "/"</B></li>
    <ul>
      <li>A new folder will automatically be created. Now create a file called <B><i>"index.md"</i></B></li>
    </ul>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=14dxAQYLrVWMqJ160hEiVOvsUPpExRlfj" align="center" height="" width="760" ></a><br><br>

<B>5. Add a brief summary of your video</B>
<ul>
  <li>After the <B><i>frontmatter</i></B> section, simply provide a brief description of the video's content and its creators.</li>
</ul>

<B>6. Commit your Changes</B>
<ul>
  <li>Scroll to the bottom of your markdown document to commit your changes</li>
  <li><B><i>Committing</i></B> will submit the markdown file to <B><i>your</i></B> fork of the Education repository</li>
</ul>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1iWHzkS8vBX8svyqwiMG50K093eWCUx9y" align="center" height="" width="760" ></a><br>

<B>7. Uploading your organization's logo</B>
<ul>
  <li>Go to <i><B>Education\_videos\videos\logos</B></i> in your fork of the Education repository.</li>
  <li>Click on "Upload Files" and drag your logo here.</li>
  <li>Commit your change</li>
</ul>

<B>8. Create a pull request</B>
<ul>
  <li>Last step!!! <a href="#pullrequest">Click here</a> to see the instructions on how to create a pull request.</li>
</ul>

</details>

### <a name= "pullrequest"></a>Step Three: Creating a Pull Request
---
***Creating a pull request*** means that you are requesting the original repository to *"pull"* or accept all the changes you just made.

<ul>
  <li><i>Do not complete this step until <B>all</B> of the materials necessary for your submission have already been uploaded to GitHub!</i></li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1LEJnnxkd2Ds8oOZPpbjUxQNqF3h1NjSl" align="center" height="" width="760" ></a>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1lmQpXfFXSgGT7M4_mbz4U73E44KdNwqD" align="center" height="" width="760" ></a><br>

### How is the Data Management Skillbuilding Hub website created?
---
The educational resources that exist in DataONE's GitHub repository are rendered into the Data Management Skillbuilding Hub webpage using Jekyll. When sharing presentations, slides themselves are rendered using remarkjs. The rendering is done using GitHub pages, which builds the site from the master branch. You can build the site locally with jekyll serve -w, and it will be available at http://localhost:4000 for you to review.

The stylesheets are defined in resources/styles, and rendered to resources/dataone.css using lessc (just type make from the root).

### <a name="tags"></a>Existing Tags
---    
access, analyze, annotation, assure, backup, calibration, citation, coding, collect, controlled vocabulary, data archives, data consistency, data creators, data management plan, data model, data normalization, data processing, data quality, data services, data source, data sources, database, date, describe, disaster, recovery, discover, documentation, file, system, flag, format, geography, geospatial, image, integrate, location, measurement, metadata, missing, values, ontologies, parameter, plan, preserve, provenance, qualify, quality, replicable data, restore, standards, storage, tabular, taxonomy, terminology, time, units
