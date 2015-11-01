---
layout: page
title: Links
---

<ul>
{% for link in site.data.links %}
    <li>
        <a href="{{ link.url }}">{{ link.title }}</a>
    </li>
{% endfor %}
</ul>