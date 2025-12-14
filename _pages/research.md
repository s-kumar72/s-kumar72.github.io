---
title: "Research"
permalink: /research/
author_profile: true
---
## Research Areas

### Advanced Manufacturing Pilot Facility (AMPF)
A short...

**Selected projects**
- **Schlieren imaging for Optomec DED mass-flow variability**  
  1–2 sentences on what you built + what you measured + the outcome.  
  [Poster PDF](/files/posters/schlieren-poster.pdf) (optional) • [Project page](/projects/schlieren/) (optional)

- **Density measurement / porosity evaluation workflow**  
  1–2 sentences + link(s) as needed.

### Aerospace Robotics Lab (ARL)
A short 2–4 sentence overview of your work at ARL (platform + autonomy goal + your role).

**Selected projects**
- **Small-form-factor lunar rover platform for multi-agent autonomy**  
  1–2 sentences + link(s) (e.g., to a project page, video, repo).
- **Electrical system architecture + power budgeting + wiring integration**  
  1–2 sentences + link(s).

## Posters
{% assign posters = site.publications | where: "type", "poster" | sort: "date" | reverse %}
{% for item in posters %}
- **{{ item.title }}** ({{ item.venue }}, {{ item.date | date: "%Y" }})  
  {% if item.pdf %}[PDF]({{ item.pdf }}){% endif %}
{% endfor %}

## Abstracts
{% assign abstracts = site.publications | where: "type", "abstract" | sort: "date" | reverse %}
{% for item in abstracts %}
- **{{ item.title }}** ({{ item.venue }}, {{ item.date | date: "%Y" }})  
  {% if item.pdf %}[PDF]({{ item.pdf }}){% endif %}
{% endfor %}
