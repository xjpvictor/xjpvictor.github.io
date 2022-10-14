This is my blog with only some random texts.

I may update randomly or not update at all.

{% for dir in site.posts %}
  {% for file in dir %}
    {% if file.extname == ".md" -%}
      {% assign filename = file.path | replace: '.md', '.html' %}
<h3><a href="{{ site.baseurl }}{{ filename }}">{{ filename }}</a></h3>
    {%- endif %}
  {% endfor %}
{% endfor %}
