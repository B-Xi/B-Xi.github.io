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

I'm also a XX  in Aerospace Information Research Institute, Chinese Academy of Sciences (CAS)

My group is recruiting master students. If interested, please send your resume and transcript to my e-mail.




<font face=STKaiti>New!</font>

<!-- Education Background
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
<!-- 
My academic experience
======
* IEEE member, member of the Chinese Society of Image and Graphics.

* I am a member of the Image Application and System Integration Professional Committee of the China Cartography Society.

* I serve as a guest editorial board member of the international journals Remote Sensing (District 2, Chinese Academy of Sciences) and Frontiers in Remote Sensing.

* I serve as a reviewer for famous international academic journals such as IEEE T-PAMI, IEEE T-NNLS, IEEE T-CSVT, IEEE T-GRS, IEEE J-STARS, Elsevier JAG-D, Pattern Recognition, etc.

* I was the president of the Xidian Student Union of the Society for International Optoelectronic Engineering (SPIE)
 -->


<!-- Awards
======
  <ul>{% for post in site.talks %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->


My Publications
======
  <!-- <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

  {% for post in site.publications %}
    {% if publications.star == "superior" %}
         {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}






Selected Blog Posts
======

<ul>{% for post in site.posts %}
    {% if post.star == "superior" %}
         {% include archive-single.html %}
    {% endif %}
  {% endfor %}</ul>

