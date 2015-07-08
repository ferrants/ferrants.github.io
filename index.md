---
layout: page
title: 
tagline: Coding, mostly
---
{% include JB/setup %}

Just a holder website until I find time to fill it out.

### Projects
- [https://github.com/dataxu/github-webhooks](https://github.com/dataxu/github-webhooks)
- [https://github.com/ferrants/github-pr](https://github.com/ferrants/github-pr)
- [https://github.com/ferrants/qball-python](https://github.com/ferrants/qball-python)
- [https://github.com/ferrants/qball](https://github.com/ferrants/qball)

### Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
