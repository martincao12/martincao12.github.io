---
layout: page
title: "Categories"
description: "在这里，你可以通过分类目录迅速地查看系列文章"  
header-img: "img/zhihu.jpg"  
---


分类目录

<ul>
    {% for category in site.categories %}
    <li><a href="/categories/{{ category | first }}/" title="view all
posts">{{ category | first }} {{ category | last | size }}</a>
    </li>
    {% endfor %}
</ul>