---
permalink: "/team/"
layout: page-fullwidth
title: "Investigadores del proyecto"
meta_title: "Equipo"
subheadline: "Conozca al equipo"

teaser: "En el proyecto RESTAURA participan geógrafos, arquitectos... La profesora Mª Yolanda Pérez-Albert, de la Universitat Rovira i Virgili, es la Investigadora Principal del proyecto, pero también participan en el proyecto investigadores del Instituto..."

meta_teaser: ""

header:
    image_fullwidth: /headers/orihuela_bajo_segura.jpg
    caption: Alguna imagen relevante.
---


<ul class="small-block-grid-2 medium-block-grid-3 large-block-grid-4">


{% for member in site.data.team %}


<li>
<div itemscope itemtype="http://schema.org/Person">

<h5>
{% if member.name %}
	{{ member.name }}<br>
{% endif %}

{% if member.lastname %}
	{{ member.lastname }}
{% endif %}
</h5>


<!-- click on image will navigate to the personal website -->
<a class="th" href="{{ member.social.first.url }}">
<img src="{{ member.pic  | prepend: "/images/team/" | prepend: baseurl  }}" alt="{{ member.name }}" style="padding:10px">
</a>

<!-- social media icons -->
<ul class="inline-list">
	{% for email in member.email %}
              <li><a href="mailto:{{ email.url }}?subject=Proyecto RESTAURA" class="{{ email.class }}" title="{{ email.title }}"></a></li>
	{% endfor %}


	{% for social in member.social %}
              <li><a href="{{ social.url }}" target="_blank" class="{{ social.class }}" title="{{ social.title }}"></a></li>
	{% endfor %}
</ul><!-- /.inline-list -->


{% if member.organization %}
	<strong>{{ member.organization }}</strong><br/>
{% endif %}

{% if member.department %}
	<i>{{ member.department }}</i><br/>
{% endif %}


<strong>Palabras clave:</strong>
<ul>
{% for keyword in member.keywords %}
	<li><code class="highlighter-rouge">{{ keyword }}</code></li>
{% endfor %}
</ul>



</div> <!-- http://schema.org/Person -->
</li>
{% endfor %}
