---
title: about
permalink: /estudios/
layout: categories
---

<p style="text-align: center;"><h1>Formacion profesional</h1></p>
<p style="text-align: center;">ASIR IES FRANCIOS DE QUEVEDO 2024</p>

<p style="text-align: center;">Lenguajes</p>
{% for lenguaje in site.data.lenguajes %}
  <p style="text-align: center;">## {{ lenguaje.nombre }} - Nivel adquirido: {{ lenguaje.nivel }}</p>
{% endfor %}
