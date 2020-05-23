Day 1 Case Study
========================================================
author: "Brad Boehmke"
date: "2019-01-31"
autosize: true



Prerequisites
========================================================

Download this folder and save it as "Intermediate-R-Case-Study-Day-1" (I know, 
I couldn't think of a longer name).  This folder will contain a "data" subfolder
that contains all the data required for this case study and a .Rmd file with
the exercises.

Exercise 1
========================================================

Create a self-contained R Project for this case study.  When creating the R 
Project, you should choose the option to create in an "Existing Directory".

## Solution

1. File,
2. New Project,
3. Existing Directory,
4. select folder you just downloaded,
5. Click "Create Project".

Exercise 2
========================================================

Open the R notebook saved as "01-case-study.Rmd".  An R notebook functions very 
similarly to an R Markdown file. In fact, you will see two files in the directory,
a 01-case-study.Rmd file and a 01-case-study.nb.html file.  Be sure to open the
.Rmd file.  

After you've opened the .Rmd file, go ahead and click the "Preview" button at the 
top of the RStudio window (next to the round settings wheel where the knit button 
used to be).  As you edit this document, rather than pressing the knit but, you 
can just hit save and your preview file will be automatically updated.  As you 
add a code chunk, run the code chunk and hit save and you will see the results 
instantly updated in your preview.

Exercise 3
========================================================

Change the author of the .Rmd file to your name and add today's date.

## Solution

```r
---
title: "Day 1 Case Study"
author: "Your name here"
date: "2019-01-31"
output: html_notebook
---
```

Exercise 4
========================================================

Run the following code chunk.  This will automatically import all the data files
and convert to a single data frame titled `df`.  Don't worry if you don't understand 
all the code, we'll discuss this more tomorrow.


## Solution

Run by pressing the green "play" button at the top right hand side of the code chunk

















```
processing file: project_pres.Rpres

Attaching package: 'dplyr'

The following objects are masked from 'package:stats':

    filter, lag

The following objects are masked from 'package:base':

    intersect, setdiff, setequal, union

Quitting from lines 85-97 (project_pres.Rpres) 
Error: '../data/Month-01.csv' does not exist in current working directory ('/Users/hena/projects/workshops/Intermediate_Rworkshop2020').
Execution halted
```
