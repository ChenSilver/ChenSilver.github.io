---
layout: page
title: story
description: 人越学越觉得自己无知
keywords: 可视化，tableau，作品集，infovis
comments: false
menu: 作品集
permalink: /infovis/
---

###### 好戏才刚刚开始！
- ####  [期中专题：我国交通运输行业（铁路与公路）的现状与发展](https://bingxin70aa.github.io/Agroup/)
- ####  [关于中国前七位蛋糕分布情况与消费水平之间的关系](https://bingxin70aa.github.io/Agroup/)
- ####  [购买力平价与消费水平之间的关系](https://bingxin70aa.github.io/Agroup/)

</br></br>
--------------------------------
> 如对该网页内容感兴趣，可以点击右边My Popular Repositories连接到我的Github库

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
