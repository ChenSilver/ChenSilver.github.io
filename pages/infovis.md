---
layout: page
title: 信息可视化设计作品集
description: 人越学越觉得自己无知
keywords: 可视化，tableau，作品集，infovis
comments: false
menu: 维基
permalink: /infovis/
---

> 记多少命令和快捷键会让脑袋爆炸呢？

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
