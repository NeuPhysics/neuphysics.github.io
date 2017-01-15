---
layout: page
---

<h1 style="text-align:center;margin-bottom:2em;"><a href="/reading">Today I Read</a></h1>


Take note when reading important papers.


{% assign readingScience = site.reading %}

<div class="tiles">
{% for post in readingScience reversed %}
	   {% include reading-list.html %}
{% endfor %}
</div><!-- /.tiles -->
