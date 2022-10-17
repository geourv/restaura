---
permalink: "/team/"
layout: page-fullwidth
title: "Investigadores del proyecto"
meta_title: "Miembros del equipo del Proyecto de investigación RESTAURA de la Universitat Rovira i Virgili (URV). Investigadora principal (IP): Maria Yolanda Pérez Albert. Membres de l'equip del Projecte d'investigació RESTAURA de la Universitat Rovira i Virgili (URV)."
subheadline: "Conozca al equipo"

teaser: "El equipo del Proyecto RESTAURA es <b>multidisciplinar</b> e <b>internacional</b>. En total, incorpora <b>34 investigadores</b> de los siguientes grupos de investigación o departamentos:"

meta_teaser: "Miembros del equipo del Proyecto de investigación RESTAURA de la Universitat Rovira i Virgili (URV). Investigadora principal (IP): Maria Yolanda Pérez Albert. Membres de l'equip del Projecte d'investigació RESTAURA de la Universitat Rovira i Virgili (URV)."

header:
    image_fullwidth: park-people2.jpg
    caption: 
---
- [Grupo de Investigación de Análisis Territorial y Estudios Turísticos (GRATET)](http://www.gratet.urv.cat/ca/). Dpto. de Geografía. Universitat Rovira i Virgili.
- [Grupo de Investigación sobre Arquitectura y Patrimonio (PATRIARQ)](https://www.etsa.urv.cat/es/investigacion/patrimoni-historic/). Escuela Técnica Sup. de Arquitectura. Universitat Rovira i Virgili.
- [Departamento de Enfermería](https://www.dinfermeria.urv.cat/es/) y [Departamento de Medicina y Cirugía](https://www.medicinaicirurgia.urv.cat/es/). Universitat Rovira i Virgili.
- [Grupo de Investigación del Movimiento Humano](https://inefc.gencat.cat/es/inefc/recerca_i_doctorat/grups_de_recerca/grup_recerca_moviment_huma/). Instituto Nacional de Educación Física de Cataluña.
- [Grupo de Diseño para la Salud y el Bienestar](https://www.eina.cat/es/investigacion/grupo-investigacion-diseno-salud-bienestar). EINA, Centro de Diseño y Arte de Barcelona. Universidad Autónoma de Barcelona.
- [Departamento de Urbanismo](http://faug.udec.cl/?page_id=14265). Universidad de Concepción (Chile).
- [Departamento de Teoría y Práctica de la Arquitectura y del Diseño](https://www.universia.net/uy/universidades/universidad-zulia.01043.html). Universidad de Zulia (Venezuela).

<iframe src="https://www.google.com/maps/d/embed?mid=1cfF900q7EPbysNt7N-zzxlrI53VSRq8&ehbc=2E312F" width="640" height="480"></iframe>

## Universitat Rovira i Virgili

<ul class="small-block-grid-2 medium-block-grid-3 large-block-grid-4">


{% for member in site.data.team1 %}


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
<img src="{{ member.pic  | prepend: "/images/team/" | prepend: "https://gratet.github.io/restaura"  }}" alt="{{ member.name }}" style="padding:10px">
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
	
{% if member.position %}
	{{ member.position }}<br/>
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
</ul>

## Institut Nacional d'Educació Física de Catalunya (INEFC)

<ul class="small-block-grid-2 medium-block-grid-3 large-block-grid-4">


{% for member in site.data.team2 %}


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
<img src="{{ member.pic  | prepend: "/images/team/" | prepend: "https://gratet.github.io/restaura"  }}" alt="{{ member.name }}" style="padding:10px">
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
	
{% if member.position %}
	{{ member.position }}<br/>
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
</ul>

## EINA, Centre Universitari de Disseny i Art de Barcelona

<ul class="small-block-grid-2 medium-block-grid-3 large-block-grid-4">


{% for member in site.data.team3 %}


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
<img src="{{ member.pic  | prepend: "/images/team/" | prepend: "https://gratet.github.io/restaura"  }}" alt="{{ member.name }}" style="padding:10px">
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
	
{% if member.position %}
	{{ member.position }}<br/>
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
</ul>

## Universidad de Concepción (Chile)

<ul class="small-block-grid-2 medium-block-grid-3 large-block-grid-4">


{% for member in site.data.team4 %}


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
<img src="{{ member.pic  | prepend: "/images/team/" | prepend: "https://gratet.github.io/restaura"  }}" alt="{{ member.name }}" style="padding:10px">
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
	
{% if member.position %}
	{{ member.position }}<br/>
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
</ul>

## Universidad de Zulia (Venezuela)

<ul class="small-block-grid-2 medium-block-grid-3 large-block-grid-4">


{% for member in site.data.team5 %}


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
<img src="{{ member.pic  | prepend: "/images/team/" | prepend: "https://gratet.github.io/restaura"  }}" alt="{{ member.name }}" style="padding:10px">
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
	
{% if member.position %}
	{{ member.position }}<br/>
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
</ul>
