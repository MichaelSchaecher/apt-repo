---
layout: default
---

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

Over the years I have developed a number of tools and scripts that have been useful to me. I have published them here in apt repositories, on github so that others can use them.
