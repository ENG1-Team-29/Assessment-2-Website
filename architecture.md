---
layout: default
permalink: /architecture/
---


# Architecture
## This is the updated UML-Diagram for version 2.0.0 of our game. You can click on each Package to view them more clearly.
<img src="/img/full.png" alt="UML diagram" usemap="#image-map" />
<map name="image-map">
{% for s in site.collections['image-map'] %}
    <area shape="poly" coords="{{ s.map.coord }}" 
          href="{{ site.baseurl }}{{ s.url }}" 
          alt="{{ s.name }}" title="{{ s.name }}" >
{% endfor %}
</map>