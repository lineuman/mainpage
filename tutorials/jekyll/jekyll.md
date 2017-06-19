---
title: "jekyll for you"
tags: [jekyll]
---


# jekyll

## jekyll var

{{ page.title }}

{{ page.url }}

{{ page.next }}

{{ page.previous }}


<hr>

{{ site.tags }}

{{ site.baseurl }}


{% for page in  site.pages %}
{{ page.title }}
{% endfor %}

{% for page in site.pages %}
{{ page.url }}
{% endfor % }}

{{ site.posts }}
