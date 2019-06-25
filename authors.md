---
title: Authors
layout: page
---

Here's a list of our author
<ul>
 {% for author in site.data.author %}
    <li>
        {{ author.name }}
    </li>
    {% endfor %}
</ul>
There's only ME, I'm all that matters !!!
