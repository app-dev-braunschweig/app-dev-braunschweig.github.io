# Welcome

This is gonna be great. Totally great. Just Awesome. Believe it.

![Beautiful Braunschweig]({{ site.url}}/assets/braunschweig.jpg)

{% for post in site.posts %}
  {{ post.excerpt }}
  <a href="{{ post.url }}">More</a>
{% endfor %}
