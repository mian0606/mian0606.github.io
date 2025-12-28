---
permalink: /
title: "Mianzhi Hu's personal webpage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



Education
======
* University of California, San Diego, Bachelor of Science (September 2024 - Present) 

Experiences and Achievements
======
* Research on AI Gaze Tracking at Prof. De Sa’s Cognitive Science Lab at UCSD (June 2025 - Present)
  * Position: Student Researcher  
  * With Convolution LSTM and Hourglass network, designed a model generating heat-maps and 3D landmarks for eyes images and coded it with PyTroch
  * Designed a CVAE network for calibration and personalized data stability with Semi-supervised Semantic Alignment mechanics, as well as group sparsity of features; trying to add personalized fine tuning tools
  * Generated 8000+ eye data with UnityEyes and collected real word datasets; designed data polluting functions with Numpy and OpenCV for model robustness, including head pose changing, swirling, Gaussian filters, upsizing, etc
  * Fleshed out the datasets to over 20000 pictures and added OpenCV techniques to refine model stability on low-quality, multi-target pictures and designing pre-calibration model by computer graphic knowledge such as Retinex and SH
  * Supervisor: Prof. Virginia De Sa, Dr. Shuangquan Feng

* Research on Image Generating & Filtering Model for Novel at Tsinghua University (May 2023 - September 2023)
  * Position: Student Researcher
  * Learned text processing technology such as snowNLP and AI image generation algorithms such as BERT, coded them out with PyTroch
  * Collected and augmented, with Stanza and basic technological skills such as banned-words, RE filtering and relativity ranking, 600+ texts (with grammar trees selecting key words) and 1300+ pictures (with Numpy and self-made style transplanting model with CNN) for model training
  * Built a novel illustration generation model with BERT & VGG; filtering out pornographic or violent results with Resnet and related models
  * Wrote a 11-pg paper; Presented at 20233rd Intl. Workshop on Frontiers of Graphics & Image Processing
  * Now Handing on refining the generation-filtering system with small batched, data-efficient semi-supervised learning and apply it to proper presentations generation, bias / false image / irrational prompts filtering;
  * Supervisor: Prof. Yi Yang and Dr. Sansi Li

* Website Including Registration and Publication System Named www.luomiart.com (August 2024 - Present)
  * Designed datasets with SQL, accommodating more than 500 articles and 100 users
  * Updated the datasets for few times while learning snowflake structure; built datasets with relationship between publication, registration payment and location data; ·With PHP, wrote code to load dynamic (small animate resources) and static resources (pictures and videos); re-organized some back end pieces such as asynchronous presentation of comments;
  * Learning ETL designing system; trying to rebuild the JAVA based data management system on Kafka (for event data capture), Spark (data processing and loading to optimized BigQuery), and Airflow (for task organizing) 
  * Personal Project
  
Skills
======
* Python and surrounding skills: Python, Pytorch, Numpy, Pandas, Pillow, COCO Tools;
* Web technology: Comprehension of IIS server tech; SQL for database; PHP for text loading, user registration
and payment services; Javascript and NodeJS;
* Programming with Java: Searching, hash, DP, graph theory, data structures, prefix algorithms, etc.;
* AI theories and technology: Image augmentation, classification, segmentation and generating tech;
large-scale image data processing and augmentation design; transformers and multimodal AI;
* Capacity to work on server clusters: basic knowledge about Virtual Machine and Linux; Nautilus
and Kubernetes and Jupiter; familiarity with Colab;
* Maths, Statistics and Machine Learning: linear algebra, calculus and statistics; maths-required
algorithms for Machine learning.

Service and leadership
======
* Formal member of HKN student group associated with UCSD CSE and ECE department, joined more than 10 reachouts to local middle schools; helped with class slides and coding issues for over 40 hours
* Member of DS3 community, a student group working on hand-on, real-world data science and AI projects




<!--
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)



For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->



