 {% assign pages = site.pages | where: "layout", page.index_layout %}
 
# Tech notes
<ul>
  {% for p in pages %}
          <li><a href="{{ p.url }}">{{ p.title }}</a></li>
  {% endfor %} 
</ul>