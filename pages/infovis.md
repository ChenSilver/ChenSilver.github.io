---
layout: page
title: story
description: 人越学越觉得自己无知
keywords: 可视化，tableau，作品集，infovis
comments: false
menu: 作品集
permalink: /infovis/
---

> 以下是信息可视化的部分作品，好戏才刚刚开始！

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
