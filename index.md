# Willkommen

Homepage der App Developer Gruppe Braunschweig.

Du hast Lust nette Android Entwickler aus dem Raum Braunschweig kennenzulernen und in lockerer Atmosphäre über aktuelle und spannende Themen aus der App Entwicklung zu diskutieren? Dann bist du hier genau richtig. Wir treffen uns in regelmäßigen Abständen an unterschiedlichen Orten. Die Termine werden über Google+ in der Android Developer Community[Android Developer Community](https://plus.google.com/communities/117412745410479171419) bekanntgegeben.

![Beautiful Braunschweig]({{ site.url}}/assets/braunschweig.jpg)

{% for post in site.posts %}
  {{ post.excerpt }}
  <a href="{{ post.url }}">More</a>
{% endfor %}
