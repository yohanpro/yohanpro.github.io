---
permalink: /my_collection/index.html
title: About me
---
{% for item in site.my_collection %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>

{% endfor %}