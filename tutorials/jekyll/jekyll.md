---
title: "jekyll for you"
tags: [jekyll]
layout: default
date:   2016-02-12 17:50:00
categories: main
---


# jekyll

## jekyll var

### page

{{ page.title }}

{{ page.url }}

{{ page.path }}

{{ page.tags }}

<hr>

{{ site.tags }}

{{ site.baseurl }}


{% for page in  site.pages %}
{{ page.title }}
{% endfor %}

## 使用循环遍历

{% for page in site.pages %}
{{ page.url }}
{% endfor %}

{{ site.posts }}
