---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Education 
======
Hohai University(https://en.hhu.edu.cn/main.psp)
Sep 2021 - Jun 2024
Master of Engineering in Environmental Science and Engineering, Hohai University
GPA: 88.73/100
Hohai University
Sep 2017 - Jun 2021
Bachelor of Engineering in Environmental science
GPA: 88.98/100


Research interest 
======
Sustainability transitions, environmental economics, industrial ecology, natural capital accounting, input-output analysis


Research Description
======
1. `Xinzi Wang`, Wenlong Zhang, Yi Li, Jiaxin Tong, Feng Yu, Quanliang Ye. (2023). Impacts of Water Constraints on Economic Outputs and Trade: A Multi-regional Input-Output Analysis in China. Journal of Cleaner Production, 434,140345. https://doi.org/10.1016/j.jclepro.2023.140345.

2. Yi Li, Xinqi Chen, `Xinzi Wang`, Jiahui Shang, Lihua Niu, Longfei Wang, Huanjun Zhang, Wenlong Zhang. (2022). The Effects of Paroxetine on Benthic Microbial Food Web and Nitrogen Transformation in River Sediments. International Journal of Environmental Research and Public Health, 19(21), 14602. https://doi.org/10.3390/ijerph192114602.

3. Wenlong Zhang, `Xinzi Wang`, Yuanyuan Miao, Yi Li, Huanjun Zhang, Lihua Niu, Longfei Wang. (2021). Determining the Effect of Sertraline on Nitrogen Transformation through the Microbial Food Web in Sediments based on 15N-DNA-Stable Isotope Probing. Environmental Research,199,111347. https://doi.org/10.1016/j.envres.2021.111347.

4. `Xinzi Wang`, Kejia Wang, Jiamu Ding, Xinqi Chen, Yi Li, Wenlong Zhang. (2021). Predicting Water Quality during Urbanization based on a Causality-based Input Variable Selection Method Modified Back-Propagation Neural Network. Environmental Science and Pollution Research, 28, 960-973. https://doi.org/10.1007/s11356-020-10514-8.


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
