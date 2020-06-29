---
layout: default 
---
{% for photo in site.photos %}
<p><a href="{{ photo.url }}"><img src="{{ photo.img }}"></a>
{% endfor %}

