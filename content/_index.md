---
date: "2022-10-24"
sections:
- block: hero
  content:
    image:
      filename: welcome.jpg
    text: |
      <br>

      Welcome to the **Factor Zoo**! We are a student lead Portfolio Management Group. On this webpage you can find information about who we are, our investment strategies and upcoming events.
    title: |
      Factor Zoo
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    page_type: post
    subtitle: null
    text: null
    title: Latest News
  design:
    columns: "1"
    view: card
- block: markdown
  content:
    subtitle: ""
    text: null
    title: null
  design:
    background:
      image:
        filename: coders.jpg
        filters:
          brightness: 1
        parallax: false
        position: center
        size: cover
        text_color_light: true
    columns: "1"
    css_class: fullscreen
    spacing:
      padding:
      - 20px
      - "0"
      - 20px
      - "0"
- block: collection
  content:
    count: 5
    filters:
      folders:
      - publication
      publication_type: article
    text: ""
    title: Articles
  design:
    columns: "1"
    view: citation
- block: markdown
  content:
    subtitle: null
    text: |
      {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    title: null
  design:
    columns: "1"
title: null
type: landing
---
