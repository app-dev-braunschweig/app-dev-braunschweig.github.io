# Welcome

This is gonna be great. Totally great. Just Awesome. Believe it.

{% for post in site.posts %}
  {{ post.excerpt }}
  <a href="{{ post.url }}">More</a>
{% endfor %}
