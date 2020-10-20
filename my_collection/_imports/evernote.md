---
layout: author
name: 剪藏
type: sort-
---

<div class="page clearfix" post>
      <ul>
        {% assign filtered_posts = site.imports | where: 'categories', page.name %}
        {% for post in filtered_posts %}
          <li><a href="{{post.url}}">{{post.title}}</a></li>
        {% endfor %}
      </ul>
</div>