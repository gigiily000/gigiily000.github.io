---
layout: archive
title: "信息可视化作品集"
date: 
modified:
excerpt: ""
tags: []
image: tableau.jpg
---
[信息可视化期末专案详细版](https://gigiily000.github.io/portfolio/tableau/%E4%BF%A1%E6%81%AF%E5%8F%AF%E8%A7%86%E5%8C%96%E6%9C%9F%E6%9C%AB%E9%A1%B9%E7%9B%AE/)
<img src="https://gigiily000.github.io/images/仪表盘.png" alt="teaser" itemprop="image">
<br/>信息可视化作品
<div class="tiles">
{% for post in site.categories.tableau%}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 tableau 的列出来-->

