<ul>
  {% for post in site.posts %}
    <li>
      <a href="blogdemo/{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>