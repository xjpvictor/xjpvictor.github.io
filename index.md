This is my blog with only some random texts.

I may update randomly or not update at all.

{% assign files = site.static_files %}
{% for file in files %}
  {% if file.extname == ".md" -%}
<h3><a href="{{ site.baseurl }}{{ file.path }}">file.basename</a></h3>
  {%- endif %}
{% endfor %}
