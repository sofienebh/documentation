---
layout: page
title: Projets
permalink: /pages/projets.html
---

## Liste des projets

{% for projet in site.data.projets %}
### {{ projet.nom }}
**Client :** {{ projet.client }}  
**Statut :** {{ projet.status }}  
{{ projet.description }}
{% endfor %}