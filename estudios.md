---
title: about
permalink: /estudios/
---

<p style="text-align: center;"># Formacion profesional</p>
<p style="text-align: center;">ASIR IES FRANCIOS DE QUEVEDO 2024</p>


<p style="text-align: center;">Lenguajes</p>
{% for lenguaje in site.data.lenguajes %}
  <p style="text-align: center;">## {{ lenguaje.nombre }} - Nivel adquirido: {{ lenguaje.nivel }}</p>
{% endfor %}