---
short_name: tldsn
name: yao-1
position: Chief Editor
---

<div class="page clearfix" post>
  <div class="left">
      <h2>Posts</h2>
      <ul>
        {% assign filtered_posts = site.posts | where: 'author', page.short_name %}
        {% for post in filtered_posts %}
          <li><a href="{{post.url}}">{{post.title}}</a></li>
        {% endfor %}
      </ul>
  </div>
</div>