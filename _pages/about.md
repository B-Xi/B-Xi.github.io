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

My group is recruiting master students. If interested, please send your resume and transcript to e-mail: xibobo@xidian.edu.cn 

Education Background
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

科研与学术经历
======
* IEEE 会员，中国图象图形学学会会员。

* 担任中国图象图形学学会图像应用与系统集成专业委员会委员。

* 担任遥感领域国际期刊 Remote Sensing（中科院二区）、Frontiers in Remote Sensing客座编委。

* 担任 IEEE T-PAMI，IEEE T-NNLS，IEEE T-CSVT，IEEE T-GRS，IEEE J-STARS，Elsevier JAG-D，Pattern Recognition 等著名国际学术期刊审稿人。

* 曾任国际光电工程学会（SPIE）西电学生会主席

项目研究经历：
======
* 主持中国博士后面上基金项目1项、陕西省博士后一等资助1项，中央高校基本科研基金项目1项，西安电子科技大学研究生创新基金项目2项。

* 参与科技创新2030“新一代人工智能”重大项目：“多源异构感知对象快速精准分割、检测、定位、 跟踪和识别的智能处理”。

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

  <ul>{% for post in site.publications %}
    {% if publications.star == "superior" %}
         {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>






Selected Blog Posts
======

<ul>{% for post in site.posts %}
    {% if post.star == "superior" %}
         {% include archive-single.html %}
    {% endif %}
  {% endfor %}</ul>

