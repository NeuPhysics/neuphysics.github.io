---
layout: archive
permalink: /
title:
---


<div class="front-cover" style="background:url(./images/{{ site.cover_image }}) no-repeat fixed center;background-size:cover;overflow:hidden;height:400px !important;">

    <section>
        <div class="container" style="padding-top:1em;">
            <h1 style="text-align:center;color:#fff;font-weight:600;" id="site-title-front">{{ site.title }}</h1>
            {% if site.description %}<h3 style="text-align:center;color:#fff;font-weight:600;font-size:90%;">{{ site.description }}</h3>{% endif %}
        </div>
<div class="featured" style="border-top:1px solid grey;margin:0 10% 0 10%;">
<div style="background-image:linear-gradient(-130deg, rgba(14,21,58,0.3) 10%, rgba(74,76,123,0.5) 35%, rgba(161,140,171,0.2) 65%, rgba(243,201,215,0.2) 90%);">
{% for post in site.posts limit:1 %}
<h3 style="text-align:center;font-size:120%;">Recent：<a href="{{ site.url }}{{ post.url }}" style="text-align:center;color:white;font-weight:600;">{{ post.title }}</a></h3>
<p style="text-align:left;color:#fff;font-size:90%;padding-bottom:0.5em;padding-left:2%;padding-right:2%;">{{ post.summary }}</p>
{% endfor %}
</div>
</div>
    </section>

</div>


------



Here is a list of projects.

* [Neutrino Document](http://neutrino.readthedocs.org/)
* [Numerical Methods](https://github.com/NeuPhysics/NumSolTUn)


-----



## Neutrino Articles

<div class="tiles">
{% for post in site.categories.neutrino limit:5 %}
	{% include post-list.html %}
{% endfor %}
</div><!-- /.tiles -->

	{% if site.categories.neutrino.size %}
<a href="./neutrino/">All Neutrino Articles ({{ site.categories.neutrino.size }})</a>
		{% else %}
No Neutrino Articles, for now.
		{% endif %}


## Neutrino Experiments

<div class="tiles">

{% for post in site.categories.experiment limit:5 %}
	{% include post-list.html %}
{% endfor %}

</div><!-- /.tiles -->



	{% if site.categories.experiment.size %}
<a href="./experiment/">All Neutrino Experiments Articles ({{ site.categories.experiment.size }})</a>
		{% else %}
No Neutrino Experiments Articles, for now.
		{% endif %}
