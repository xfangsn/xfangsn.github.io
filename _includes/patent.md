<h1 id="patent"></h1>

<h2 style="margin: 60px 0px 10px;">Patents</h2>


{% for link in site.data.patents.contents %}
<li>
<strong>[{{ link.date }}]</strong> {{ link.title }}, {{ link.country }}, {{ link.id }}
</li>
{% endfor %}
