---
layout: author
name: tldsn
type: sort-
---

<!-- <div class="page clearfix" post>
  <div class="left">

  </div>
</div> -->

<div class="page clearfix" post>
      <!-- <h2>{{ page.name }}</h2> -->
      <ul>
        {% assign filtered_posts = site.posts | where: 'author', page.name %}
        {% for post in filtered_posts %}
          <li><a href="{{post.url}}">{{post.title}}</a></li>
        {% endfor %}
      </ul>
</div>