---
title: Campervan
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 10
    pagination: true
---

{% for p in page.collection %}
<h2>{{ p.title }}</h2>
{{ p.summary }}
{% endfor %}