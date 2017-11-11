---
title: 'Fiches de revision'
content:
    items: '@self.children'
---

{% for p in page.collection %}
<h2>{{ p.title }}</h2>
{{ p.summary }}
{% endfor %}