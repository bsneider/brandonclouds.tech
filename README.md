---
layout: default
title: Home
nav_order: 1
description: "BrandonClouds.Tech the hope of all things Cloud, CloudNative, DevOps, Security, and Education"
permalink: /
---

# Welcome to BrandonClouds.tech

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
