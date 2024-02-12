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

My group is recruiting master students. If interested, please send your resume and transcript to my e-mail.

Education Background
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

My academic experience
======
* IEEE member, member of the Chinese Society of Image and Graphics.

* I am a member of the Image Application and System Integration Professional Committee of the China Cartography Society.

* I serve as a guest editorial board member of the international journals Remote Sensing (District 2, Chinese Academy of Sciences) and Frontiers in Remote Sensing.

* I serve as a reviewer for famous international academic journals such as IEEE T-PAMI, IEEE T-NNLS, IEEE T-CSVT, IEEE T-GRS, IEEE J-STARS, Elsevier JAG-D, Pattern Recognition, etc.

* I was the president of the Xidian Student Union of the Society for International Optoelectronic Engineering (SPIE)

My project experience：
======
* I presided over 1 China Postdoctoral Fund Project, 1 Shaanxi Province Postdoctoral First-class Fund Project, 1 Central Universities Basic Research Fund Project, and 2 Xi'an University of Electronic Science and Technology Graduate Student Innovation Fund Projects.(主持中国博士后面上基金项目1项、陕西省博士后一等资助1项，中央高校基本科研基金项目1项，西安电子科技大学研究生创新基金项目2项。) 

* 

* I participated in the major project of Science and Technology Innovation 2030 "New Generation Artificial Intelligence": "Intelligent processing of rapid and accurate segmentation, detection, positioning, tracking and identification of multi-source heterogeneous sensing objects". (我参与科技创新2030“新一代人工智能”重大项目：“多源异构感知对象快速精准分割、检测、定位、 跟踪和识别的智能处理”。)

Awards
======
  <ul>{% for post in site.talks %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Publications
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

