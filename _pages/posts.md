---
layout: single
title: "Posts"
permalink: /posts/
author_profile: true
sidebar:
    nav: "posts"
---
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}