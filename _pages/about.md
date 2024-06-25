---
permalink: /
title: #"Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a (final year-) Ph.D. student in Computer Science at the Georgia Institute of Technology, advised by Dr. Thomas Ploetz. At Georgia Tech, I am associated with the Computational Behavior Analysis and Ubiquitous Computing Lab. I am on the industry job market and am interested in opportunities that align with my skill set. Looking forward to making contributions towards exciting work. 

Research Interest
------
My research interest broadly focuses on building novel activity recognition pipelines for wearable and nearable sensing devices. During the course of my Ph.D. I have focused on developing machine learning algorithms for activity monitoring and behavior analysis. 
My dissertation builds pipelines for recognizing activities in smart homes, by observing data collected from residents using nearable sensors. 
As such I propose a ``**lifespan**" of a human activity recognition system in smart homes, which includes (a) initial bootstrapping procedure - aimed at `jump-starting' the activity recognition system in the home, with minimal supervision from the resident, without considerable wait times; (b) updating and extending the activity recognition system - aimed at improving the recognition capabilities of the initial bootstrapped system; (c) routine assessment - aimed at behavior monitoring of residents over extended periods of observation. 

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

