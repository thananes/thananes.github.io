---
title: about
permalink: /estudios/
layout: categories
---

##Formacion profesional
ASIR IES FRANCISCO DE QUEVEDO 2024

Lenguajes
{% for lenguaje in site.data.lenguajes %}
  ## {{ lenguaje.nombre }} - Nivel adquirido: {{ lenguaje.nivel }}
{% endfor %}
