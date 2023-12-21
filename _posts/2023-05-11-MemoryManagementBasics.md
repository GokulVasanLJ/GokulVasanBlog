---
layout: distill
title: Memory Management Basics
description: Understanding Reverse Mapping in Linux (Level 2 topic)
date: 2023-12-12

authors:
  - name: Gokul Vasan
    url: "https://abstractcomputation.com"
    affiliations:
      name: TUKL, Germany

bibliography: 2018-12-22-distill.bib

# Optionally, you can add a table of contents to your post.
# NOTES:
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
#   - we may want to automate TOC generation in the future using
#     jekyll-toc plugin (https://github.com/toshimaru/jekyll-toc).
toc:
  - name: The Need
    # if a section has subsections, you can add them as follows:
    # subsections:
    #   - name: Example Child Subsection 1
    #   - name: Example Child Subsection 2
  - name: Implementation Overview

# Below is an example of injecting additional post-specific styles.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px;
  }


---

**NOTE:**
I categrorize my writing based on the depth of the topic. 
The depth implies the level of understanding the reader need to prior possess to understand the article.
For Example: assume an article has a depth of "Level 2", it meant the user may find it hard to comprehend the article without understanding certain other article presented in the first level. 