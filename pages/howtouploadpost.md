---
title: "How to upload post"
keywords: sample homepage
tags: [Guildline]
sidebar: mydoc_sidebar
permalink: howtopostupload.html
summary: It is description about how to upload post
---

## How to add new topic int the sidebar

Edit _data/sidebars/mydoc_sidebar.yml

### 1. Make big category
  - title: Guildline
    output: web, pdf
    folderitems:
    
### 2. Make small category below the big category
    - title: How to upload post
      url: /howtouploadpost.html
      output: web, pdf
      type: homepage

## How to upload post in the project category

Add pages/decs/ .md

### 1. Add the basic information
---
title: "Comparative Genomics Project Description"
keywords: sample homepage
tags: [Project Description]
sidebar: mydoc_sidebar
permalink: comparativegenomics_proj.html
summary: It is description about comparative genomics project
---

### 2. Fill the contents
## Build the Theme

Follow these instructions to build the theme.





{% include links.html %}
