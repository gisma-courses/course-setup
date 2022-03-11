---
title: "Best Practice Scripts & Functions in R"
toc: true
toc_label: content
header:
  image: "/assets/images/code.png"
  caption: "gisma via gisma-corses"

---
Opinions differ widely on how best to organize the programming workflow in general and the development of scripts and functions in particular. The probably supreme rule is to remain consistent in the naming of functions, variables, etc.. You will see in the example scripts that this is not as easy as it looks like...

In order not to overstretch the arch, the following sources are worthwhile a visit - complexity is ascending...<!--more-->
- [r-bloggers](https://www.r-bloggers.com/r-code-best-practices/){:target="_blank"} best practices introduction
- [Efficient R programming](https://csgillespie.github.io/efficientR/coding-style.html){:target="_blank"} Coding style
- [USGS](https://owi.usgs.gov/blog/intro-best-practices/){:target="_blank"} best practices introduction


For the beginning it is a recommendation to start a script with a header that includes information about script type  author, scripts purpose, inputs and outputs if appropriate used/usable data and legal stuff. In addition it is very helpful to keep inline with a structure that addresses your workflow. That means something like a fixed structure loading packages, sourcing files, defining variables and so on.

A basic first corpus may look like below. Please note just write meaningful stuff into the header it is not a punishment but for clarification. 


```r
# ===============================================================================
# Name:      xyz.R
#
# Author:    Chris Reudenbach, creuden@gmail.com
#
# Purpose:   script creates this and that for necessary purposes
#
# Input:     useful data
#
# Output:    a nice raster
#
# Remarks:   blablabla
# Copyright: Chris Reudenbach, Thomas Nauss 2017-2021, GPL (>= 3)
# ===============================================================================


# 0 - load packages
#---------------------


# 1 - source files
#---------------------


# 2 - define variables
#---------------------


# 3 - start code 
#--------------------


```

## Introduction to functions

The use of function is imperative and ubiquitous the sooner you start the better. The principle is simple: Identify processes that are performed more than once and pack them into your own independent script:

Have a look at the [R function](https://swcarpentry.github.io/r-novice-inflammation/02-func-R/) exercises.

