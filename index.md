Intro paragraph
## posts
<ul>
  {% for p in site.posts %}
	 <li>{{p.date}} - <a href="{{site.baseurl}}/{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %} 
</ul>