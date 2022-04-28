---
title: "Arlin Kalenchuk"
layout: splash
permalink: /
hidden: true
date: 2022-04-27T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash.jpg
  actions:
    - label: "Download Resume"
      url: /assets/Arlin-Kalenchuk-Resume.pdf
  caption: ""
excerpt: "Product Manager, Computer Vision Expert, Web Developer, Fabricator, Always leveling up"

feature_row:
  - image_path: assets/images/vision.jpg
    alt: "Computer Vision"
  - image_path: /assets/images/vision3.jpg
    alt: "cameras"
  - image_path: /assets/images/fabricator.jpg
    alt: "welding"

 
gallery:
  - url: /assets/images/gallery1.jpg
    image_path: /assets/images/gallery1.jpg
    alt: "gallery1"
  - url: /assets/images/gallery2.jpg
    image_path: /assets/images/gallery2.jpg
    alt: "gallery2"
  - url: /assets/images/gallery3.jpg
    image_path: /assets/images/gallery3.jpg
    alt: "gallery3"
  - url: /assets/images/gallery4.jpg
    image_path: /assets/images/gallery4.jpg
    alt: "gallery3"
  - url: /assets/images/gallery5.jpg
    image_path: /assets/images/gallery5.jpg
    alt: "gallery5"
    
feature_row2:
  - image_path: /assets/images/gallery1.jpg
    alt: "Media Portfolio"
    title: "Media Portfolio"
    excerpt: ''
    
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include gallery caption="Photography Portfolio" %}

{% include feature_row id="feature_row2" type="center" %}

{% include feature_row id="feature_row3" type="right" %}

