---
title: 100 Days of Code
---

A blog of my journey of 100 Days of Code

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
<!-- {{ site.baseurl }}{% post_url 2018-12-31-a-new-years-eve-test %} -->
