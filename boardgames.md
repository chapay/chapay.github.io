---
layout: page
title: Boardgames
---

<ul>
{% for boardgame in site.data.boardgames %}
    <li>
        <a href="{{ boardgame.url }}">{{ boardgame.title }} ({{ boardgame.year }})</a>
    </li>
{% endfor %}
</ul>