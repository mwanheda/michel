---
layout: markdown
title: Définitions
permalink: /definitions
id: definitions
---

<h1 class="mb-5">Définitions</h1>

## Mise en contexte des objets connectés 

**Que sont-ils ?**

L’Internet des objets constitue un grand réseau parmi lequel on retrouve l’ensemble des appareils connectés au réseau Internet tel que des imprimantes, des téléphones cellulaires, des machines à café, des machines à laver, des lumières, etc. (Guarana, 2018)

L’Internet des objets permet ainsi à une panoplie d’objets qui n’était pas originalement conçue pour être connectée à Internet, de l’être. Ces objets physiques interagissent entre eux et transmettent des données à un réseau. Ce réseau permet aux objets d’être connectés à Internet (Ibid). 

## Diverses définitions 

{% for definition in site.data.definitions %}
<span class="mr-2" style="color: var(--primary);">{{ definition.word }}</span> {{ definition.def }}
{% endfor %}
