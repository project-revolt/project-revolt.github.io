---
layout: page
permalink: /other/
title-nolink: Other
---
<!--- <ul>
    {% for post in site.tags.critiques %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul> --->

<ul>
 {% for post in site.categories.other %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>