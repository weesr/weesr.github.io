---
permalink: /submission/
title: "Call for papers"
author_profile: true
classes: wide
redirect_from: 
  - /call-for-papers/
---


{% capture submissions %}
#### Submissions
Please send your papers using [the official SPLC EasyChair instance](https://easychair.org/conferences/?conf=splc2022). You must select the WEESR workshop before submitting your paper. 
{% endcapture %}
<div class="notice--success">{{ submissions | markdownify }}</div>
{% capture publication %}

#### Publication
SPLC workshop papers will be published in volume 2 of the SPLC conference proceedings published by ACM.
{% endcapture %}
<div class="notice--success">{{ publication | markdownify }}</div>


{% capture instructions %}
#### Instructions
* Submissions must must be written in English according to the 2019 [ACM Master Article Template](https://www.acm.org/publications/proceedings-template)
* Papers must be at most 8 pages, including figures, tables and references.
* All the papers must be electronically submitted by [EasyChair](https://easychair.org/conferences/?conf=splc2022)
* All submissions will be reviewed by at least two (2) experts.
{% endcapture %}
<div class="notice">{{ instructions | markdownify }}</div>

~~~~
%% LaTeX instructions
%% If you are using LaTeX, please use the following template and conference information:

\documentclass[sigconf]{acmart}
~~~~




