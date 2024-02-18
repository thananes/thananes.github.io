---
title: about
permalink: /estudios/
layout: posts
---

##Formacion profesional
ASIR IES FRANCIOS DE QUEVEDO 2024

Lenguajes
{% for lenguaje in site.data.lenguajes %}
  ## {{ lenguaje.nombre }} - Nivel adquirido: {{ lenguaje.nivel }}
{% endfor %}
