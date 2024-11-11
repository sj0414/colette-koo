---
permalink: /
title: "Hello, I'm Colette."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am expected to graduate with a Bachelor of Science in Computer Science and Engineering from Konkuk University. Currently, I work as an undergraduate research assistant at the Virtual Reality Laboratory, focusing on research in computer graphics under the guidance of Professor Hyungseok Kim. Previously, I also worked as a research assistant under the advisement of Professor Haewon Byun, engaging in deep learning studies, where I gained hands-on experience in developing and applying machine learning models.

My main interests lie in **computer graphics, digital twins, realistic rendering and animation**. I am passionate about developing lifelike rendering techniques and animation to create immersive digital environments that closely replicate the physical world.

My Journey in Computer Graphics Research and Personal Passions
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

News
======

### 2024

- **Jul., 2024 - Present**: Working as an Undergraduate Research Assistant under Professor Hyungseok Kim.
- **Dec., 2024**: Successfully completed Graduation Project on developing a *Conference Record Management Service Using Computer Vision*.
- **Jun., 2024**: Successfully completed the *Image Matching System Development Project*.
- **Jun., 2024**: Completed development of an app that helps users locate nearby medical facilities and provides quick guidance on emergency response actions.
- **May, 2024**: Presented on *Documentation, Organization, and Planning*.
- **May, 2024**: Awarded **Excellence Award** at Wrtn Technologies Inc. 2nd Ideathon, Generative AI Ideathon at Konkuk University.
- **Feb., 2024**: Successfully submitted the *Nanuming* project for the 2024 GDSC Solution Challenge, offering a contactless sharing service for baby care products through a self-designed *Nanuming Box*.

### 2023

- **Nov., 2023**: Competed in an AI competition on Dacon to predict prices of specialty products from Jeju, achieving **top 21%** with my AI team.
- **Dec., 2023**: Successfully completed the project and presentation for *Emergency Pet Management and Dispatch Service*.
- **Dec., 2023**: Successfully completed a family management app development project that allows all family members to participate.
- **Sep., 2023**: Presented my startup idea on *Emergency Pet Management and Dispatch Service*, and was selected as the **Top Student**.
- **Jun., 2023**: Successfully completed a personal routine management and assistant application development project.
- **Jun., 2023**: Successfully completed a project developing a system for *Object Recognition in Videos*, focusing on face detection and hand detection.
- **May, 2023**: Selected as a member of the **STARTUP021 Entrepreneurship Club**.

### 2022

- **Sep., 2022**: Won the **Gold Prize** at the Software Innovation Competition at Sungshin Women’s University.
- **Jan. - Jun., 2022**: Worked as an Undergraduate Research Assistant under Professor Haewon Byun.

### 2021

- **Sep., 2021**: Successfully submitted a project for the Software Innovation Competition at Sungshin Women’s University, developing a game to help children prevent and escape from disaster and emergency situations.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
