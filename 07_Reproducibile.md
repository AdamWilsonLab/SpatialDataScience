---
title: "Reproducible Research and R Markdown"
date: 2018-10-10 
subtitle: 
reading:
   - 
presentation:
   - day_13_repro.html
tasks:
   - Learn how to read R help files effectively
   - Learn how to search for help
   - Learn how to create a Minimum Working Example (MWE)
---





<div class='extraswell'>
  <button data-toggle='collapse' class='btn btn-link' data-target='#pres'>View Presentation </button>      [Open presentation in a new tab](presentations/day_13_repro.html){target='_blank'}
<div id='pres' class='collapse'>
<div class='embed-responsive embed-responsive-16by9'>
  <iframe class='embed-responsive-item' src='presentations/day_13_repro.html' allowfullscreen></iframe>
  _Click on presentation and then use the space bar to advance to the next slide
   or escape key to show an overview._
</div>
</div>
</div>


## Download

| [<i class='fas fa-code fa-2x' aria-hidden='true'></i><br>  R Script]( scripts/07_Reproducibile_nocomments.R ) | [<i class='fa fa-file-code-o fa-2x'></i> <br> Commented R Script]( scripts/07_Reproducibile.R ) | [<i class='far fa-file-alt fa-2x'></i> <br>  Rmd Script]( scripts/07_Reproducibile.Rmd )|
|:--:|:-:|:-:|


## R Markdown

Cheatsheet:

<a href="https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf"> <img src="07_assets/rmarkdown.png" alt="alt text" width="400"></a>

<small><small><small>[https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)</small></small></small>

## Overview
Today we will make a copy of a template for your final project, edit it, and 'push' it back up to your github account.  You can check out the template code at [https://github.com/AdamWilsonLab/RDataScience_Project](https://github.com/AdamWilsonLab/RDataScience_Project) and the template website at [http://adamwilson.us/RDataScience_Project/](http://adamwilson.us/RDataScience_Project/)

## `Fork` the repository to create a linked copy in your GitHub account.

Steps:

1. Go to https://github.com/AdamWilsonLab/RDataScience_Project
2. Log into Github using your account (or create a new account)
3. Click `fork` near the upper right corner.  This will create a copy in your GitHub Account.  [See here for more details](https://help.github.com/articles/fork-a-repo/)
4. After it completes, click the green button "Clone or Download" and copy the URL.

## Clone the project template to your computer

1. **File -> New Project -> Version Control -> Git**
  * URL: paste from above.  It will be similar to  `https://github.com/AdamWilsonLab/RDataScience_Project.git` but with your username.
  * Project name: you can rename it if you want or keep the default: `RDataScience_Project`
  * Project as subdirectory of `~/Documents/repos` or wherever you want to put it.
2.  It should download the project to your computer then open it to the `index.Rmd` file.

## Play with the project template

1. Select the `Build` tab in the upper right corner of RStudio, then click `Build Website`
2. Check out the website settings in `_site.yml`.  These adjust the appearance, title, etc.
3. Check out `_navbar.yml`.  These settings define the menus, etc.  If you only have one page you probably won't need to adjust this information.  

## Push to GitHub and enable the website
1. Select the `Git` tab in the upper right and notice how it keeps track of any changes.
  * To 'commit' the files (which is like saving them), check the files you want to commit (or all of them) and click `commit`.
  *  Type in a brief message about the changes you made.  Maybe something like "First update to my project materials"
  * Click `Commit`, then `close`.
  * Click `Push` to push it back up to GitHub.
2. Now go to your repository website (similar to [https://github.com/AdamWilsonLab/RDataScience_Project](https://github.com/AdamWilsonLab/RDataScience_Project) in your account)
3. Click settings in the upper right, then scroll down to `GitHub Pages` section
   * Source: `master branch /docs folder`
4. Go to your new project webpage (URL will be similar to [http://adamwilson.us/RDataScience_Project/]( http://adamwilson.us/RDataScience_Project/))
5.  Now you can `commit` and then `push` your updates and your website will be updated.  If you get tired of entering your username and password every time, check out the instructions [here](http://adamwilson.us/RDataScience/GitSSHNotes.html).  

## Explore markdown functions

1. Use the Cheatsheet to add sections and some example narrative.  
2. Try changing changing the species name to your favorite species and re-run the report. 
3. Add more figures or different versions of a figure
4. Check out the `kable()` function for tables (e.g. `kable(head(d))`)

<a href="https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf"> <img src="07_assets/rmarkdown.png" alt="alt text" width="400"></a>

> Abandoning the habit of secrecy in favor of process transparency and peer review was the crucial step by which alchemy became chemistry.<small>Raymond, E. S., 2004, The art of UNIX programming: Addison-Wesley.</small>
