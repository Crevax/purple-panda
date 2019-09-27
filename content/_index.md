---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      I love technology and am always learning something new. I also believe in sharing useful or interesting information, so this site will help with that purpose.
  - section_id: about
    component: content_block.html
    type: contentblock
    title: About
    content: >-
      Someday I'll flesh out more details here.
    actions:
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: posts_block.html
    type: postsblock
    title: Recent Posts
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
layout: home
menu:
  main:
    weight: 1
    name: Home
---
