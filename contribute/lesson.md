---
title: Contributing to Lessons
layout: generic
---
# Contributing a Lesson to the Data Management Skillbuilding Hub
###  Step One: Forking DataONEorg's Education Repository    
---  
> **Items necessary for this step:**      
> - [x] your own GitHub account online     

<details>
<summary style="color:teal;"><B>Instructions</B></summary>
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

### <a name="lesson"></a>Step Two: Submitting the Lesson
---
> **Items necessary for this step:**     
> - [x]  a text file (e.g. a Word document, Notepad, Google Docs, any text editor, etc.)
> - [x]  your organization's logo (.PNG only)
> - [x] your lesson, and any additional files

<details>
<summary style="color:teal;"><B>Instructions</B></summary><br>

<B>Creating the "frontmatter" file</B><br>

For every lesson submitted to the Skillbuilding Hub, an additional file, named <B>index.md</B>, must be submitted with it. This document contains the metadata and formatting information for the lesson. This information is also called the <B><i>"frontmatter"</i></B>.<br><br>

<B>The following information is needed when submitting educational materials to the Data Management Skillbuilding Hub:</B><br><br>

<ul>
  <li><B>title:</B>The full title of your lesson</li>
  <li><B>author:</B> a list of authors that created the lesson</li>
  <li><B>organization:</B> name of organization that oversaw the creation of the lesson</li>
  <li><B>org_url:</B> website of the organization, organization logo will open this webpage when selected</li>
  <li><B>org_logo:</B> name of the organization’s logo file <i><B>(this must be a .png file).</B></i></li>
  <li><B>update:</B> the date this lesson was created</li>
  <li><B>layout:</B> is always <i><B>lesson_cover</B></i> for all lessons</li>
	<li><B>status:</B> is always <i><B>published</B></i></li>
  <li><B>tags:</B> a list of (short) keywords describing the content of the best practice text</li>
    <ul>
      <li> Click <a href="#tags">here</a> for a list of currently existing tags</li>
    </ul>
  <li><B>categories:</B> this must be listed as <i><B>["Teaching Module"]</B></i></li>
  <li><B>previous lesson:</B> The name of the previous lesson according to its numeric assignment. <a href="https://github.com/DataONEorg/Education/tree/master/_lessons/lessons" target="_blank" junk="_" >Click here to see the current list of lessons.</a></li>
  <li><B>next lesson:</B> The name of the following lesson according to its numeric assignment</li>
  <li><B>handout:</B> <i>[Optional]</i> If you have a handout to contribute, paste the exact name of the handout here as well as its extension</li>
  <li><B>powerpoint:</B> The exact name of your powerpoint followed by its extension</li>
  <li><B>exercise:</B> <i>[Optional] </i>If you have an exercise to contribute, paste the exact name of the exercise here as well as its extension</li>
</ul><br>

<b>2. Copy the following text block and paste it into your empty text file</b>    
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

<B>3. Fill out the appropriate information for each of the categories</B>

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

Now your frontmatter information is completed. <B><i>Save your text file</i></B>, and we will copy and paste this text at a later step in the submission process.<br><br>


<B>4. Create a folder for your files in your fork of the Education repository on GitHub.</B><br><br>

With a lesson, you will have to submit multiple items. Consequently, you must first make a <B>folder</B> to contain everything!<br><br>

<ul>
  <li><B>The folder naming convention is as follows:</B> <i>(a number) _ (the name of your lesson)</i></li>
    <ul>
      <li>The number at the beginning should be the next one in the sequence according to the number of lessons that already exist in the repository. <a href="https://github.com/DataONEorg/Education/tree/master/_lessons/lessons" target="_blank" junk="_">Click here to see the current list of lessons.</a></li>
    </ul>
  <li><B>To create the folder</B>, go to <i>`(yourGitHubAccount)/Education/_lessons/lessons`</i> and click <B>"Create New File"</B></li>
  <ul>
    <li>Type the name of your folder followed by <B>a slash "/"</B>. The slash automatically creates a new folder.</li>
      <ul>
        <li>Now create a file called <B><i>"index.md"</i></B> within your folder. <i><B>This file is going to contain the frontmatter for your lesson.</B></i></li>
        </ul>
  </ul>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1YUdOwtm0FK6z0WqFVjlHLYk_DhHAdfDa" align="center" height="" width="760" ></a><br><br>  

<B>5. Copy the "frontmatter" saved in your text file from Step One and paste it here into the markdown (.md) file</B>
  <ul>
    <li><i>Be sure to include the three dashes at the beginning and end of the section</i></li>
  </ul><br>

<B>6. Add a brief summary of your lesson</B>
<ul>
  <li>After the <B><i>frontmatter</i></B> section, simply type out a brief explanation of what problem your lesson is addressing and what methods it proposes for solving it.</li>
</ul><br>

<B>7. Commit your Changes</B>
<ul>
  <li>Scroll to the bottom of your markdown document to commit your changes</li>
  <li><B><i>Committing</i></B> will save the markdown file to <B><i>your</i></B> fork of the Education repository</li>
</ul>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1J1MJUBcvpyMSRFGOKy8I2-JT2i6Vyb8v" align="center" height="" width="760" ></a><br>

<B>7. Upload lesson files</B>
<ul>
  <li>If you are contributing files that are already created, simply click <B><i>"Upload Files"</i></B> in the upper right-hand corner, and drag and drop all the files you are submitting.</li>
  <li><B>Before</B> you drag and drop your items, <B>rename</B> them so that they follow the correct <B>file naming convention.</B></li>
  <li><B>Each submission type has its own file naming convention:</B></li>
    <ul>
      <li><B>Slideshow:</B> `(your lesson number)_(your lesson topic).(ext)`</li>
      <ul>
        <li><B>Example:</B> `01_management.pdf`</li>
      </ul>
      <li><B>Handout:</B> `L(your lesson number)_(your lesson topic)_Exercise.(ext)`</li>
      <ul>
        <li><B>Example:</B> `L02_DataSharing_Handout.pdf`</li>
      </ul>
      <li><B>Exercise:</B> `L(your lesson number)_Exercise.(ext)` </li>
      <ul>
        <li>Example: `L02_Exercise.pdf`</li>
      </ul>
      <li><B>Supplementary data:</B> `DataFiles_L(your lesson number).ext`</li>
      <ul>
        <li><B>Example:</B> `DataFiles_L04.zip`</li>
      </ul>
    </ul>

	<li>Alternatively, you can also <B><i>create a slideshow directly from within GitHub using Markdown</i></B>. Creating a Markdown powerpoint allows users to play the slideshow directly from their browser. <B>No downloading necessary!</B></li>
  <ul>
    <li>To do this, simply click <B><i>"Create New File"</i></B> in the upper right-hand corner, and name it <i><B>slides.md</B></i></li>
		  <li>Markdown is an <i>extremely lightweight, easy-to-read, easy-to-write, and easy-to-learn</i> language! <a href="https://github.com/saraneh/Education/blob/master/_lessons/lessons/00_markdown">HERE is a quick and straightforward resource on creating a lesson in Markdown.</a></li>
		  <li><i><B>Note that spaces, indents, lines, and dashes are actually very important here, so be sure to follow the formatting of the example as closely as possible!</B></i></li>
	  </ul>
	 </ul><br>

<B>8. Upload your organization's logo</B>
<ul>
  <li>Go to `(yourGitHubAccount)/Education/_lessons/lessons/logos` in your fork of the Education repository.</li>
  <li>Click on "Upload Files" and drag your logo here.</li>
  <li>Commit your change</li>
</ul>

</details>

### <a name= "pullrequest"></a>Step Three: Creating a Pull Request
---
<details>
<summary style="color:teal;"><B>Instructions</B></summary><br>

<B><i>Creating a pull request</i></B> means that you are requesting the original repository to <B>"pull"</B> or accept all the changes you just made.

<ul>
  <li><i>Do not complete this step until <B>all</B> of the materials necessary for your submission have already been uploaded to GitHub!</i></li>
</ul>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1LEJnnxkd2Ds8oOZPpbjUxQNqF3h1NjSl" align="center" height="" width="760" ></a>
<a href="url"><img src="https://drive.google.com/uc?export=view&id=1lmQpXfFXSgGT7M4_mbz4U73E44KdNwqD" align="center" height="" width="760" ></a><br><br>

<B>That's it! You have completed all the steps.</B> Once someone has approved your pull request, you will be able to find your submission in DataONE's repository.
<br><br>

</details>

### Step Four: Submitting to the Data Management Training Clearinghouse
---
<details>
<summary style="color:teal"><B>Instructions</B></summary>

<B>The Data Management Training (DMT) Clearinghouse</B> is an online registry for learning resources regarding data management. In other words, listing your submission on the Clearinghouse is required because it increases the amount of people who discover and benefit from your submission.

<ul>
  <li>To submit to the Clearinghouse, you need:</li>
    <ol>
      <li>The <B>title</B> of your submission</li>
      <li>The <B>URL</B> for your submission</li>
        <ul>
          <li>Your URL does not actually exist yet until the DataONEorg branch has approved your submission.</li>
          <li>Once you have received an email that your submission has been merged with DataONEorg's repository, go to the <B><i>folder where your lesson</i></B> exists and use the folder address as the URL for submitting to the Clearinghouse.</li>
        </ul>
      </ol>
  </ul><br>

<a href="url"><img src="https://drive.google.com/uc?export=view&id=1Pvhh-cMX6ZbR3fuXSd4tGtB7_Ge9HQlL" align="center" height="" width="760" ></a><br><br>

<button style="font-size:150%;" onclick="window.location.href = 'https://dmtclearinghouse.esipfed.org/submit';">Submit to the Clearinghouse</button>

</details>
### How is the Data Management Skillbuilding Hub website created?
---
The educational resources that exist in DataONE's GitHub repository are rendered into the Data Management Skillbuilding Hub webpage using Jekyll. When sharing presentations, slides themselves are rendered using remarkjs. The rendering is done using GitHub pages, which builds the site from the master branch. You can build the site locally with jekyll serve -w, and it will be available at http://localhost:4000 for you to review.

The stylesheets are defined in resources/styles, and rendered to resources/dataone.css using lessc (just type make from the root).

### <a name="tags"></a>Existing Tags
---    
access, analyze, annotation, assure, backup, calibration, citation, coding, collect, controlled vocabulary, data archives, data consistency, data creators, data management plan, data model, data normalization, data processing, data quality, data services, data source, data sources, database, date, describe, disaster, recovery, discover, documentation, file, system, flag, format, geography, geospatial, image, integrate, location, measurement, metadata, missing, values, ontologies, parameter, plan, preserve, provenance, qualify, quality, replicable data, restore, standards, storage, tabular, taxonomy, terminology, time, units
