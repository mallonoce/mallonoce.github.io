---
layout: landing
header: true
footer: true
title: CV
excerpt: >
  This is my CV
permalink: /cv

article_header:
  height: 100vh
  theme: dark
  background_color: "#111"
  background_image:
    gradient: "linear-gradient(rgba(240, 0, 150, .4), rgba(104, 0, 208 , .4))"
data:
  sections:
    - title: Freelancer
      excerpt: I'm working as a fulltime freelancer 
      theme: dark
      background_color: "#515151"
    - title: Software Engineer
      excerpt: Seeone Vision Technology and cuda developer
      actions:
        - text: See my projects!
          url: /projects.html
        - text: Look my library
          url: /projects.html
      image:
        src: /screenshots/TeXt-layouts.png
        is_row: true
        full_width: true
        style: "max-width: 1200px;"
    - title: Computer Vision Researcher
      excerpt: University "La Sapienza" Of Rome. 
      image:
        src: /screenshots/TeXt-skins.png
        is_row: true
        full_width: true
        style: "max-width: 1000px;"
    - title: Computer Vision Researcher
      excerpt: Vicomtech research center
      image:
        src: /screenshots/TeXt-skins.png
        is_row: true
        full_width: true
        style: "max-width: 1000px;"
    - title: Master's Degree
      children:
        - title: Thesys
          excerpt: TeXt offer some CSS classes for your page, including alert, tag, image, button, etc.
          actions:
            - text: Learn More
              url: /docs/en/additional-styles
        - title: Extensions
          excerpt: Adding audios, videos, slides and demos to your page.
          actions:
            - text: Learn More
              url: /docs/en/extensions
        - title: Markdown Enhancements
          excerpt: Using Mathjax, Mermaid and Charts in your page.
          actions:
            - text: Learn More
              url: /docs/en/markdown-enhancements
    - title: 100% Free
      theme: dark
      excerpt: Free to use however you want under the MIT License. Clone it, fork it, customize it, whatever!
      actions:
        - text: '<i class="fab fa-github"></i> GitHub'
          url: https://github.com/kitian616/jekyll-TeXt-theme
      background_color: "#515151"
    - title: Tip Me
      children:
        - title: 'WeChat <i class="fas fa-arrow-down"></i>'
          image:
            src: /docs/assets/images/tip_wechat.jpg
            style: "max-width: 200px; max-height: 200px"
            is_row: true
        - title: 'Alipay <i class="fas fa-arrow-down"></i>'
          image:
            src: /docs/assets/images/tip_alipay.jpg
            style: "max-width: 200px; max-height: 200px"
            is_row: true
        - title: 'PayPal <i class="fas fa-arrow-down"></i>'
          image:
            src: /docs/assets/images/tip_paypal.jpg
            url: https://www.paypal.me/kitian616
            style: "max-width: 200px; max-height: 200px"
            is_row: true
---