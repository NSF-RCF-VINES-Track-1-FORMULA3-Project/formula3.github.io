---
title: News
layout: page
---

{% for post in site.news reversed %}
## {{ post.title }}

{{ post.date | date: "%B %d, %Y" }}

{{ post.content }}

---
{% endfor %}
