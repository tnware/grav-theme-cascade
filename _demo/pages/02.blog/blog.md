---
title: Blog
external_links:
    process: true
    title: false
    no_follow: true
    mode: active
    target: _blank
body_classes: 'header-image fullwidth'
sitemap:
    changefreq: monthly
blog_url: blog
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---

# My Gravtastic Blog
## A tale of **awesomazing** adventures
