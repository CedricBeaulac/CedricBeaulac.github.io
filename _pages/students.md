---
layout: archive
title: "Students"
permalink: /students/
author_profile: true
---

This page contains a mixed bags of things. First, I have included a list of unpublished articles, notes and informal talks. Most of these were not prepared for publications, but I really wanted to make all of that information publicly available, if you use anything please cite it. This page also contains some of my appearances in various university related promotional material. 

Unpublished work and talks
======

  {% for post in site.miscellaneous reversed %}
    {% include archive-single.html %}
  {% endfor %}
