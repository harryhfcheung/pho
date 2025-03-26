---
layout: default
title: Main page
---

## Overview

Welcome to my personal webpage. Here you'll find blog posts, projects, and other content related to my interests in math, physics and programming. This site is powered by [Jekyll](https://jekyllrb.com) and hosted on GitHub Pages.

---

<h1>Latest Blog Post</h1>

{% assign latest_post = site.posts | first %}

<article>
  <h2><a href="{{ site.baseurl }}{{ latest_post.url }}">{{ latest_post.title }}</a></h2>
  <p><small>{{ latest_post.date | date: "%B %-d, %Y" }}</small></p>
  <div>{{ latest_post.excerpt }}</div>
</article>
