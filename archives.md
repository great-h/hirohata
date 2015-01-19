---
layout: page
title: 過去のレポート
permalink: /archives/
---

<ul class="posts">
  {% for post in site.posts reversed %}
    <li>
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
