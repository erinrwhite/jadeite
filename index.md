Intro paragraph
## posts
<ul>
  {% for p in site.posts %}
	 <li>{{ p.date | date: "%Y-%m-%d" }} - <a href="{{site.baseurl}}{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %} 
</ul>