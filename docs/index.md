---
title: Geo Information Science Basics
layout: splash
date: '2018-02-06 13:00:00 +0100'
header:
  overlay_color: "#000"
  overlay_filter: 0.6
  overlay_image: '/assets/images/working-environment.png'
  caption: '[Image](https://pixabay.com/de/users/joffi-1229850/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1359136) [joffi via Pixabay](https://pixabay.com/de/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1359136)'  
  cta_label: Go to course units
  cta_url: "/units.html"
  cta_url: "/downloads.html"
excerpt: Basic Course Information for GI courses.
feature_row_intro:
- excerpt: Master level course in [Physical Geography](https://www.uni-marburg.de/fb19/studium/studiengaenge/msc-phygeo) at Marburg University
feature_row_ilos:
- image_path: "/assets/images/envobs_ilos.jpg"
  alt: PC monitor laying in the garden of the institute.
  title: Intended learning outcomes
  excerpt: "Template..."
---


{% include feature_row id="feature_row_intro" type="center" %}

One could claim that the fact living on the surface of the earth and only get to know a small space through direct personal experience is the most important motivation for most of the geographic work. Compensation for this lack of direct experience has been and is being made, especially in scientific geography, with the help of efficient spatio-temporal techniques of abstraction. 

Knowledge of spatial and/or temporal aspects of our environment is increasingly in demand for action-relevant relationships. Whether we ask as tourists, consumers, producers or planners spatial information, or even knowledge. 

Geographic Information Science (GIS) is based on versatile and powerful software tools that are used in modeling, analysis, data mining merging and numerous other spatio-temporal applications. Nevertheless the most powerful tool is our mind developing the concepts and developing the necessary algorithms.

# Intended learning outcomes
At the end of this course you should be able

* to understand, adapt and develop geographic information science methods 
* to design workflows suitable to solve common spatio temporal data-related issues
* to deploy your workflows using geo-information science tools, R scripts and collaborative code management platforms for task management and issue tracking
* to critically evaluate your spatiao-temporal analysis
* to communicate your workflow and analysis results



# Preparation and prerequisites

The courses assumes basic knowledge and skills in R Remote Sensing and GIS. Due to be linked  to each other you may obtain the required R, Remote Sensing and GIS skills by the parallel courses [Data Analysis](https://geomoer.github.io/moer-mpg-data-analysis/){:target="_blank"}, [Geo Information Systems](https://geomoer.github.io/moer-mpg-gis/){:target="_blank"} and [Remote Sensing]( geomoer.github.io/moer-mpg-remote-sensing/){:target="_blank"}. 

It is intended as a blended learning module in our study program although the provided introductions, explanations and examples might be useful for self-study, too. Data and examples in this course focus on Marburg Open Forest - the open research and learning forest of Marburg University - and are related to the LOEWE Priority Programm [Nature 4.0](https://www.uni-marburg.de/de/fb19/natur40){:target="_blank"}.


# Deliverables

The graded course certificate will be based on a portfolio hosted as a repository on GitHub. The individual portfolio items are defined in the respective course assignments along with the information if they will be marked or not. Marked portfolio items encompass the presentation and peer-review the paper which inform about the results of two problem solving assignments related to the computation and analysis of the remote sensing and geographic information systems products.


# Instructor
{% include author-profile.html %}

# Authors


{% for author in site.data.authors %} 
  {% include author-profile.html %}
 <br /> 
{% endfor %}