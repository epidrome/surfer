---
layout: default 
---
{% for photo in site.photos %}
<p><a href="{{ photo.url }}"><img src="/img/{{ photo.img }}"></a>
{% endfor %}

