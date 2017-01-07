---
title: Department ideas
---

{% for image in site.images %}
     {% if image.extname == 'jpg' %}
         <img src="{{ file.url }}" />
     {% endif %}
{% endfor %}
