---
title: "jekyll for you"
tags: [jekyll]
layout: default
---


# jekyll
## 注意
当你指明了data和catagory时，会被映射到另一个路径
## jekyll var

### page

{{ page.title }}

{{ page.url }}

{{ page.path }}

{{ page.tags }}

<hr>

{{ site.tags }}

{{ site.baseurl }}

## 文章列表
<ul>
{% for post in site.posts %}
<li>{{ post.url }} {{ post.title }}</li>
{% endfor %}
</ul>


{% for page in  site.pages %}
{{ page.title }}
{% endfor %}

## 使用循环遍历

{% for page in site.pages %}
{{ page.url }}
{% endfor %}

{{ site.posts }}
