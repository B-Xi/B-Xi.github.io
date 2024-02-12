---
permalink: /
title: <center><a href="https://B-Xi.github.io/" title="Bobo Xi">Bobo Xi (席博博)</a></center>
# excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently an associate professor at School of Telecommunications Engineering, Xidian University, and also a member of the  State Key Laboratory of Integrated Service Networks.

I'm also 空间中心



Education Background
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <!-- <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

  <ul>{% for post in site.publications %}
    {% if publications.star == "superior" %}
         {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>


Competitions
======
  <ul>{% for post in site.talks %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>



Selected Blog Posts
======

<ul>{% for post in site.posts %}
    {% if post.star == "superior" %}
         {% include archive-single.html %}
    {% endif %}
  {% endfor %}</ul>

