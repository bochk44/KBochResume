# **POSTING A RESUME IN MARKDOWN TO GITHUB**

By following this guide, you will be able to post your [resume](https://bochk44.github.io/KBochResume.github/Resume), formatted in [Markdown](https://www.markdownguide.org/), to [Github](https://github.com/). This guide is broken up into 4 parts: <a href="#first_step">Setting up Atom</a>, <a href="#second_step">Writing a Resume in Markdown</a>, <a href="#third_step">Posting it to Github</a>, and <a href="#fourth_step">Formatting it with Jekyll</a>.

---

## A) <a id="first_step">Setting up Atom for Markdown</a>


This section is intended to help you set up the necessary tools for effectively working with Markdown. There are many other editors that you could use but this is one of the more popular and straightforward options.

  1. Download [Atom](https://atom.io/) for creating your Markdown files <br> <br>
  2. Open up Atom and click on the "File" tab in the top right corner <br> <br>
  3. Click "Settings" which should open up a new tab for Settings<br> <br>
![Settings Screenshot](README_Pictures/Screenshot1.jpg) <br> <br> <br>
  4. Click "Packages"<br> <br>
![Packages Tab Screenshot](README_Pictures/Screenshot2.png) <br> <br> <br>
  5. Use the search bar to find and download the packages "language-markdown", "markdown-writer", and "markdown-preview" <br> <br>
![Packages Download Screenshot](README_Pictures/Screenshot3.png) <br> <br>

  6. Ensure Atom is now fully funtional with Markdown by opening a new file titled "HelloWorld.md" (Note: all Markdown files __MUST__ end with ".md").
  7. Type the following into your file:<br>
```markdown
# Hello World!
Welcome to the world of Markdown!
```
  8. Click the "Packages" tab at the tob and find "Markdown Preview" and select "Toggle Preview" <br> <br>
![Packages Screenshot](README_Pictures/Screenshot4.png) <br> <br>
  9. Verify that you are now looking at something something similar to the following screen <br> <br>
![Packages Screenshot](README_Pictures/Screenshot5.png) <br> <br>

**You are now ready to begin working with Markdown!**

---

## B) <a id="second_step">Writing a Resume in Markdown</a>


This section is intended to help guide you through building your resume. It is rather short compared to the rest as this is not truly the focus of this guide. Instead, this will simply try to give you the tools and couple helpful tips for making the conversion easier. <br>

  1. Plan how you want your resume to look. If you have one written in another format, break it up into chunks and pick the order you want it to be read in. Otherwise, start by laying out the basics like work experience, skills, and any other info you think might be relevant. <br> <br>
  2. Write the basic info in the order you want and identify the main sections and headers. <br> <br>
  3. Using [this guide](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) adjust the formatting to fit what you believe to be important by creating headers and using line breaks to emphasize the chuncks you came up with in the last step. Try to keep it somewhat simple for now since the exact formatting may be altered when we apply Jekyll to it later. <br> <br>

---

## C) <a id="third_step">Posting a Markdown Page to Github</a>


This section is intended to help you navigate and understand how to use github for the purpose of hosting a page. <br>

  1. Open your Github account. If you do not have one, create an account. <br> <br>
  2. Create a new repository. You can do this by clicking on the plus symbol in the top right corner of your screen and selecting "New Repository" from the drop down menu. <br> <br>
  3. Fill in the details on the "Create a New Repository page". For the sake of postig your resume this means coming up with a name (which likely should be something with some part of your name and the word resume), selecting it to be public, and checking the box to initialize it with a README. Whether you want to provide a description or not is entirely up to you. <br> <br>
  4. Ensure the information is filled out correctly and click the "Create Repository" button at the bottom of the page. <br> <br>
  5. Click the "Upload Files" button just to the left of the bright green "Clone or Download" button. <br> <br>
  6. Select your resume file from your home directory to add it to your new repository. <br> <br>
  7. Open the settings for your repository. This can be found on the main page of your repository. <br>
  ![Github Settings Screenshot](README_Pictures/Screenshot6.png) <br> <br>
  8. Scroll down the page to find the Github Pages section and change your "Source" to being "master branch".<br> <br>
  ![Github Pages gif](README_gifs/enable_github_pages.gif) <br> <br>
  9. Adjust the README file that came pre-built into your repository (assuming you did check the box from step 3 saying you wanted a README included). Currently, your Github page will default to opening your README so you can either include a link to your resume in the readme or copy and paste your resume code into the README. <br> <br>
  
  

---

## D) <a id="fourth_step">Fomatting a Markdown Page with Jekyll</a>


This section is intended to help you format your resume and improve on the basic Markdown appearence. Much of this will be applying a theme and ensuring that all the elements of your Markdown file appear as desired. <br>

  1. Click on the setting tab in your repository. <br> <br>
