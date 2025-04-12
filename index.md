# Tech notes
<ul>
 {% assign posts = site.posts %}
  {% for p in posts %}
	 <li><a href="{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %} 
</ul>