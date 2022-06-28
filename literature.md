---
layout: page
permalink: /literature/
title-nolink: Literature
---
<ul>
    {% for post in site.categories.literature %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<!---<ul>
    {% for post in site.tags.literature %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>--->

<!-- ## Check out our literature blog posts:
- [One-Dimensional Man](/_posts/2021-03-15-test.md)
- [Eros and Civilization](/_posts/2021-03-15-test.md)
- [Caliban and the Witch](/_posts/2021-03-15-test.md)
- [Pokemon](/_posts/2021-03-15-test.md) -->