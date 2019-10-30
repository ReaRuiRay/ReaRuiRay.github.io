---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-2.jpg
  actions:
    - label: "About me"
      url: "/about"
  caption: "Blue Hills during Fall"
excerpt: "I am an atmospheric scientist interested in applying the best techniques to benefit the society. "
intro: 
  - excerpt: 'My works are classified into the following categories. Why not give each a peek? '
feature_row:
  - image_path: /assets/images/research-2.png
    image_caption: "Air pollution in U.S." 
    alt: "Research picture"
    title: "Research"
    url: /researches
  - image_path: /assets/images/portfolio.jpg
    image_caption: "IoT and PCB DIY"
    alt: "Portfolio picture"
    title: "Portfolio"
    url: "/portfolio"
  - image_path: /assets/images/blog.jpg
    image_caption: "AGU presentation"
    alt: "Blog picture"
    title: "Blog"
    url: "/posts"
---

{% include feature_row id="intro" type="center"%}

{% include feature_row %}