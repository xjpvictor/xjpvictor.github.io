This is my blog with only some random texts.

I may update randomly or not update at all.

{% for post in site.posts %}
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
<p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong></small></p>
{% endfor %}