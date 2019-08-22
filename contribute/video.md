---
title: Contribute
layout: generic
---
# Contributing a Video to the Data Management Skillbuilding Hub

### Step One: Forking DataONEorg's Education repository
---
---
> **Items necessary for this step:**      
> - [x] your own GitHub account online     

<head>
<style> .indented { padding-left: 50pt; padding-right: 50pt; } </style>
</head>

<details>
<summary style="color:teal"><B>Instructions</B></summary>
<br>

<B><img src="https://drive.google.com/uc?export=view&id=1IrXJwH3BoS_Zpb5MZi04YMjqeFHvQBTU" align="center" height="" width="5%" > Forking a repository</B><br>

To submit content to the Skillbuilding Hub, you need to first <B>create a fork</B> of DataONEorg's Education repository. This means you will be creating <B><i>your own private copy</i></B> of the Education repository and storing it in your <B><i>GitHub account online</i></B>. Here, <i><B>in your fork</B></i>, you can edit and upload content <B><i>without affecting the original</i></B>.The forking process will take a few minutes at most. Once you've perfected your changes, you will later <B>merge</B> the changes you have made back into the original repository.<br><br>

<B>1. Create an account online at <img src="https://drive.google.com/uc?export=view&id=1ovyl_eW1AhSYCqEsp8jsb0VsPebNT0EG" align="center" height="" width="1.5%" > <a href="https://github.com" target="_blank" junk="_">GitHub</a>, if you don't already have one.</B><br><br><br>

<B>2. To start the forking process, go to DataONEorg's <a href="https://github.com/DataONEorg/Education" target="_blank" junk="_">Education repository</a>.</B><br><br><br>

<B>3. In the right hand corner of DataONEorg's Education repository, click the "fork" button.</B>

<ul>
  <li>Make sure you are logged into your GitHub account before you press fork.</li>
</ul>

<img src="https://drive.google.com/uc?export=view&id=1KJ3kvkiB0WbixBEfN54GuGWhgLs-qYC6" align="center" height="" width="760" class="indented"><br><br>

<B>4. The forking process is complete!</B> Check "your repositories" in your account to make sure the Education repository was successfully forked.<br><br>

<B>5. Download a PNG file of your organization's logo onto your computer</B>
<ul>
  <li>If you are associated with a university, company, or other organization you must include their logo along with your submission.</li>
  <li>Once you have downloaded the logo, make sure to name the .PNG after your organization</li>
  <li><B><i>For now the PNG will be saved on your desktop, but later we will upload it to a specific location in DataONE's GitHub repository</i></B></li>
</ul>
</details>

### <a name="video"></a>Step Two: Submitting the Video
---
---
> **Items necessary for this step:**     
> - [x]  a text file (e.g. a Word document, Notepad, Google Docs, any text editor, etc.)
> - [x]  your organization's logo (.PNG only)
> - [x] the embed link for your video

<details>
<summary style="color:teal"><B>Instructions</B></summary><br>

<B>Submitting a Video</B><br>

Videos are too large to be stored directly in DataONEorg's repository. Consequently, your video submission <i><B>must already be uploaded to a video streaming platform,</B></i> such as <B>YouTube, Vimeo, Facebook,</B> etc.

Instead of uploading a video to DataONEorg's repository, <B>you will be submitting a document</B> which contains the video metadata (also known as <B><i>"frontmatter"</i></B>) and the source code (also known as <B><i>SRC</i></B>) for the video. The source code is what allows the video to be displayed on the Skillbuilding Hub website.<br><br>

<p><b>The following information is needed when submitting educational materials to the Data Management Skillbuilding Hub:</b></p>
<ul>
  <li><B>title:</B> the full title of your video</li>
  <li><B>layout:</B> is always <i><B>video_cover</B></i></li>
  <li><B>tags:</B> a list of (short) keywords describing the content of the video</li>
    <ul>
      <li><a href="#tags"> a list of currently existing tags</a></li>
    </ul>
  <li><B>step:</B> a list of one or more steps of the data lifecycle to which the video applies.</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/blob/master/_lessons/lessons/02_datasharing/02_datasharing.pdf" target="_blank" junk="_">Learn about the data lifecycle</a></li>
    </ul>
  <li><B>related:</B> <i><B>(optional)</B></i> Choose one or a few other videos in the DataONE repository that are related to yours. List the folder name of the video</li>
    <ul>
      <li><a href="https://github.com/DataONEorg/Education/tree/master/_videos/videos" target="_blank" junk="_"> a list of existing videos</a></li>
    </ul>
  <li><B>update:</B> the date this video was created</li>
  <li><B>author:</B> a list of authors that created the video</li>
  <li><B>video_embedurl:</B> the SRC portion of your video's embed code. Instructions on where to find this can be found in <a href="#embed">Step 3</a>.</li>
  <li><B>organization:</B> name of organization that oversaw the creation of the video</li>
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

Now your frontmatter information is completed. <B><i>Save your text file</i></B>, and we will copy and paste this text at a later step in the submission process.<br><br>

<a name= "embed"></a><B>3. Getting the Embed Code and SRC for your Video</B>

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
<img src="https://drive.google.com/uc?export=view&id=1eufRbGbD3OrM-3uPlb0Pag5KuhzTsByO" align="center" height="" width="50%" class="indented"> <br><br>

<B>4. Create a folder for your files</B><br>

With a video, you will have to create folder in your fork as well as a markdown file to go inside of it.

<ul>
  <li>The folder should be named after the first three words of your video title, separated by dashes</li>
  <li>In your fork, go to <i>`(yourGitHubAccount)/Education/_videos/videos`</i> and click <B>"Create New File"</B>, located in the upper right-hand corner</li>
  <li>Type the name of your folder followed by <B>a slash "/"</B></li>
    <ul>
      <li>A new folder will automatically be created. Now create a file called <B><i>"index.md"</i></B></li>
    </ul>
</ul>

<img src="https://drive.google.com/uc?export=view&id=14dxAQYLrVWMqJ160hEiVOvsUPpExRlfj" align="center" height="" width="50%" class="indented" ><br><br>

<B>5. Copy the "frontmatter" saved in your text file from Step One and paste it here into the markdown (.md) file</B>
  <ul>
    <li><i>Be sure to include the three dashes at the beginning and end of the section</i></li>
  </ul><br>

<B>6. Add a brief summary of your video</B>
<ul>
  <li>After the <B><i>frontmatter</i></B> section, simply provide a brief description of the video's content and its creators.</li>
</ul>

<B>7. Commit your Changes</B>
<ul>
  <li>Scroll to the bottom of your markdown document to commit your changes</li>
  <li><B><i>Committing</i></B> will submit the markdown file to <B><i>your</i></B> fork of the Education repository</li>
</ul>
<img src="https://drive.google.com/uc?export=view&id=1sm_ngCHroF7m1Yd8ozPmXRI044ON_6ta" align="center" height="" width="50%" class="indented"><br><br>

<B>8. Uploading your organization's logo</B>
<ul>
  <li>Go to <i>`(yourGitHubAccount)/Education/_videos/videos/logos`</i> in your fork of the Education repository.</li>
  <li>Click on "Upload Files" and drag your logo here.</li>
  <li>Commit your change</li>
</ul>
</details>

### <a name= "pullrequest"></a>Step Three: Creating a Pull Request
---
---
<details>
<summary style="color:teal"><B>Instructions</B></summary><br>

<B><i>Creating a pull request</i></B> means that you are requesting the original repository to <B>"pull"</B> or accept all the changes you just made.

<ul>
  <li><i>Do not complete this step until <B>all</B> of the materials necessary for your submission have already been uploaded to GitHub!</i></li>
</ul>

<img src="https://drive.google.com/uc?export=view&id=1LEJnnxkd2Ds8oOZPpbjUxQNqF3h1NjSl" align="center" height="" width="760" >
<img src="https://drive.google.com/uc?export=view&id=1lmQpXfFXSgGT7M4_mbz4U73E44KdNwqD" align="center" height="" width="760" ><br>

<B>That's it! You have completed all the steps.</B> Once someone has approved your pull request, you will be able to find your submission in DataONE's repository.
<br>
</details>

### How is the Data Management Skillbuilding Hub website created?
---
---
The educational resources that exist in DataONE's GitHub repository are rendered into the Data Management Skillbuilding Hub webpage using Jekyll. When sharing presentations, slides themselves are rendered using remarkjs. The rendering is done using GitHub pages, which builds the site from the master branch. You can build the site locally with jekyll serve -w, and it will be available at http://localhost:4000 for you to review.

The stylesheets are defined in resources/styles, and rendered to resources/dataone.css using lessc (just type make from the root).

### <a name="tags"></a>Existing Tags
---    
---
access, analyze, annotation, assure, backup, calibration, citation, coding, collect, controlled vocabulary, data archives, data consistency, data creators, data management plan, data model, data normalization, data processing, data quality, data services, data source, data sources, database, date, describe, disaster, recovery, discover, documentation, file, system, flag, format, geography, geospatial, image, integrate, location, measurement, metadata, missing, values, ontologies, parameter, plan, preserve, provenance, qualify, quality, replicable data, restore, standards, storage, tabular, taxonomy, terminology, time, units
