---
title: "Research"
permalink: /research/
author_profile: true
---
## Research Areas

### Advanced Manufacturing Pilot Facility (AMPF)
The Advanced Manufacturing Pilot Facility (AMPF) at Georgia Tech is a 20,000-square-foot, reconfigurable research and development high-bay facility that bridges the gap between laboratory research and real-world manufacturing deployment. As the flagship facility of the Georgia Tech Manufacturing Institute (GTMI), AMPF brings together faculty, students, and industry partners to collaboratively develop, scale, and demonstrate advanced manufacturing technologies — from additive/hybrid manufacturing and digital manufacturing to robotics, automation, and AI-enabled systems — and to translate early-stage concepts into implementable solutions. It also serves as a teaching laboratory and workforce development hub, supporting academic research, industry collaborations, and training programs/

**Selected projects**
- **Schlieren Imaging for Gas Flow Visualization in the Optomec DED Printer**  
  1–2 sentences on what you built + what you measured + the outcome.  
  [Poster PDF](/files/posters/schlieren-poster.pdf) (optional) • [Project page](/projects/schlieren/) (optional)

- **Alternative Sealing Methods for Density Testing of Porous Additively Manufactured Parts**  
  1–2 sentences + link(s) as needed.

### Aerospace Robotics Lab (ARL)
A short 2–4 sentence overview of your work at ARL (platform + autonomy goal + your role).

**Selected projects**
- **Small-form-factor lunar rover platform for multi-agent autonomy**  
  1–2 sentences + link(s) (e.g., to a project page, video, repo).

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
