---
layout: default
title: "Inicio"
permalink: /
---

# {{ site.title | default: "Mi sitio" }}

{{ site.description | default: "Notas y artículos." }}

<hr/>

{% comment %}
Si más adelante activás paginación, este bloque ya contempla paginator si existe,
y sino usa site.posts (todos los posts).
{% endcomment %}
{% assign items = paginator.posts | default: site.posts %}

{% if items and items.size > 0 %}
  {% for post in items %}
  <article style="margin:1rem 0;">
    <h2 style="margin:0;">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>

    {% if post.excerpt %}
      <p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
    {% endif %}

    <p><a href="{{ post.url | relative_url }}">Leer más →</a></p>
  </article>
  <hr/>
  {% endfor %}

  {% if paginator %}
  <nav style="display:flex; gap:1rem; align-items:center;">
    {% if paginator.previous_page %}
      <a href="{{ paginator.previous_page_path | relative_url }}">&laquo; Más nuevas</a>
    {% endif %}
    <span>Página {{ paginator.page }} de {{ paginator.total_pages }}</span>
    {% if paginator.next_page %}
      <a href="{{ paginator.next_page_path | relative_url }}">Más antiguas &raquo;</a>
    {% endif %}
  </nav>
  {% endif %}

{% else %}
  <p>Aún no hay publicaciones.</p>
{% endif %}

<hr/>

<p>
  <a href="{{ "/about/" | relative_url }}">Acerca de…</a>
</p>
