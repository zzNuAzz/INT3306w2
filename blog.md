---
layout: default
title: Blog
---

<div class="container">
  <div class="pt-4">
    {% for post in site.data.posts %}
    {% include post.md 
        postTitle = post.title
        postImg = post.img
        postTime = post.time
        postBody = post.body
        %}

    {% endfor %}
  </div>
</div>