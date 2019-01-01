# Blog Home

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


## [100 Days of Code](100-days-of-code)

Sharing my experience with the 100 Days of Code Challenge!
