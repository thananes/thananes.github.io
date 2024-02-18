---
title: about
permalink: /estudios/
---

<div style="text-align: center;">

![Descripción de la imagen](/banner.jpg)


# Formacion profesional
ASIR IES FRANCIOS DE QUEVEDO 2024

Lenguajes
{% for lenguaje in site.data.lenguajes %}
  ## {{ lenguaje.nombre }} - Nivel adquirido: {{ lenguaje.nivel }}
{% endfor %}

</div>
