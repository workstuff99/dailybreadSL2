---
layout: page
title: Daily Word
---

{% for post in site.daily reversed %}
- **{{ post.date | date: "%B %d, %Y" }}**  
  [{{ post.title }}]({{ post.url }})
{% endfor %}
