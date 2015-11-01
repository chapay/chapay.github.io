---
layout: page
title: Bookshelf
---

<ul>
{% for data in site.data.books %}
    <h2>{{ data.year }}</h2>

    <ul>
    {% for book in data.books %}
        <li>
            "{{ book.title }}" ({{ book.year }}) - <em>{{ book.authors }}</em>
        </li>
    {% endfor %}
    </ul>
{% endfor %}
</ul>