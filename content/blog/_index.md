---
title: Blog
description: |
  A blog that will act as my digital garden.
author: "Allison Keever"
show_post_thumbnail: true
show_author_byline: true
show_post_date: true
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Digital Garden 
  description: |
    This blog is my digital garden. Where ideas can grow and evolve. You will find an assortment of my thoughts, ideas, and experiences, as well as updates on recent projects.  
    <br>
    "Each flower, tree, and vine is seen in relation to the whole by the gardener so that the visitors can have unique yet coherent experiences as they find their own paths through the garden." 
    <br><br><br>
    <i class="fas fa-mug-hot pr2"></i>If my blog has helped you, you can [buy me a coffee](https://ko-fi.com/)!
  author: "Allison Keever"
  text_link_label: Subscribe via RSS
  text_link_url: /index.xml
  #text_link_label: If my blog has helped you, you can buy me a coffee
  #text_link_url: https://ko-fi.com/
  show_sidebar_adunit: false # show ad container


# set up common front matter for all pages inside blog/
cascade:
  author: "Allison Keever"
  show_author_byline: true
  show_post_date: true
  show_comments: true # see disqusShortname in site config
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /blog/
    show_sidebar_adunit: false # show ad container

---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**
