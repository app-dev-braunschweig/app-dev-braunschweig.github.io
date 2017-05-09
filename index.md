# Willkommen

Homepage der App Developer Gruppe Braunschweig. 

![Beautiful Braunschweig]({{ site.url}}/assets/braunschweig.jpg)

{% for post in site.posts %}
  {{ post.excerpt }}
  <a href="{{ post.url }}">More</a>
{% endfor %}
