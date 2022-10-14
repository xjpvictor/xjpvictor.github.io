This is my blog with only some random texts.

I may update randomly or not update at all.

{% for page in site.html_pages %}
<p><a href="{{ page.url }}">{{ page.title }}</a><br>
<span style="font-size:.8em;font-weight:bold;">{{ page.date | date: "%B %e, %Y" }}</span></p>
{% endfor %}
