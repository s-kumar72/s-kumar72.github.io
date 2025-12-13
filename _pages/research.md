---
title: "Research"
permalink: /research/
author_profile: true
---

## Posters
{% assign posters = site.publications | where: "type", "poster" | sort: "date" | reverse %}
{% for item in posters %}
- **{{ item.title }}** ({{ item.venue }}, {{ item.date | date: "%Y" }})  
  {% if item.pdf %}[PDF]({{ item.pdf }}){% endif %}
{% endfor %}
