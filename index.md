<ul>
  {% for post in site.posts %}
    <li>
      <a href="blogdemo/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>