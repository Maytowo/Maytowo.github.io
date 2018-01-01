---
layout: archive
title: "信息可视化作品集"
modified:
excerpt: "Tableau"
tags: []
image: 
  feature: 300x200.gif
  teaser:
 ---
 在此展示网页设计与制作内容简绍及思考
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>