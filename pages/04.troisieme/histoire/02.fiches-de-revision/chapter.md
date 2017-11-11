---
title: 'Fiches de revision'
process:
    twig: true
    markdown: false
content:
    items: '@self.children'
---

Voici les fiches de revision d'Histoire

<ol>
{% for p in page.collection %}
<li>{{ p.title }}</li>
{% endfor %}
</ol>