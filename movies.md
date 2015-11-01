---
layout: page
title: Movies
---

<ul>
{% for data in site.data.movies %}
    <h2>{{ data.year }}</h2>

    <ul>
    {% for movie in data.movies %}
        <li>
            <a href="{{ movie.url }}">{{ movie.title }} ({{ movie.year }})</a>
        </li>
    {% endfor %}
    </ul>
{% endfor %}
</ul>