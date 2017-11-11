---
title: 'Fiches de revision'
process:
    twig: true
    markdown: false
content:
    items: '@self.children'
---

Voici les fiches de revision d'Histoire

{{ dump(page.collection[page.path]) }}

<ol>
{% for p in page.collection %}
    <li><a href="{{ '' }}">{{ p.title }}</a></li>
{% endfor %}
</ol>