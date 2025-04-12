# Tech notes

Intro paragraph.

## posts
<ul>
  {% for p in site.posts %}
	 <li><a href="{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %} 
</ul>