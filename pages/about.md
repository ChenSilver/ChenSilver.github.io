---
layout: page
title: About
description: 打码改变世界
keywords: Zhuang Ma, 马壮
comments: true
menu: 关于
permalink: /about/
---

我是冰昕，网络与新媒体专业的大学生。

不断尝试，永不停歇。

坚信熟能生巧，努力改变人生。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})

## 感谢朋友与老师的帮助

{% for website in site.data.links %}
* {{ website.name }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}