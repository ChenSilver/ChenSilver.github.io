---
layout: page
title: web
description: 没有链接的博客是孤独的
keywords: web,网页,设计,作品集
comments: true
menu: 作品集
permalink: /porfolio/
---

> God made relatives. Thank God we can choose our friends.

{% for link in site.data.links %}
* [{{ link.name }}]({{ link.url }})
{% endfor %}
