---
title: "jekyll for you"
tags: [jekyll]

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

## site内的所有标签
{{ site.pages }}


## 文章列表

{% for post in site.posts %}
{{ post.url }} {{ post.title }}
{% endfor %}



{% for page in  site.pages %}
{{ page.title }}
{% endfor %}

## 使用循环遍历

{% for page in site.pages %}
{{ page.url }}
{% endfor %}


