---
layout: page
title: Bookshelf
---

<ul>
    {% for book in site.data.books %}
        <li>
            <a href="{{ book.url }}">{{ book.title }}</a> - <em>{{ book.authors }}</em>
        </li>
    {% endfor %}
</ul>