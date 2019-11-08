
<ul>
  {% for post in site.posts %}
    <li>
      <h2>{{post.type}}</h2>
      <a href="{{site.baseurl}}/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
