---
title: "Home"
layout: splash
permalink: /

intro: 
  - excerpt: "**Hello and welcome to my portfolio website!** <br><br> **Work In Progress**"
feature_row:
  - #image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - #image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    #image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - #image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

project_highlight:
  - image_path: assets\images\thesisMainPicture.png
    image_url: /projects/thesis
    alt: "Picture of thesis project"
    title: "Escape Room Digital Minigames Further Development"
    excerpt: "This is my thesis I did as part of my studies in Karelia University of Applied Sciences. In my thesis I examined and further developed an Escape Room's Digital Minigames, which were used by University of Eastern Finland to research and develop computational thinking skills.
    <br>
    <br>You can view my thesis in Theseus in Finnish or go to **Read More** section for an English summary."
    url: "/projects/thesis"
    btn_label: "Read More"
    btn_class: "btn--primary"
    url2: "https://urn.fi/URN:NBN:fi:amk-2023110928934"
    btn_label2: "Link to Theseus"
    btn_class2: "btn--primary"
    
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="project_highlight" type="center" %}

{% include feature_row %}

