---
layout: default
---

{% for post in site.posts %}
- <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
{% endfor %}
