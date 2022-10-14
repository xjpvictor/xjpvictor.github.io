This is my blog with only some random texts.

I may update randomly or not update at all.

{% for page in site.html_pages %}
<h3><a href="{{ page.url }}">{{ page.title }}</a></h3>
<p><small><strong>{{ page.date }}</strong></small></p>
{% endfor %}
