---
title: "Research"
permalink: /research/
author_profile: true
---
## Research Areas

### Advanced Manufacturing Pilot Facility (AMPF)
The Advanced Manufacturing Pilot Facility (AMPF) at Georgia Tech is a 20,000-square-foot, reconfigurable research and development high-bay facility that bridges the gap between laboratory research and real-world manufacturing deployment. It also serves as a teaching laboratory and workforce development hub, supporting academic research, industry collaborations, and training programs.

I've been an undergraduate research assistant at the AMPF since Spring 2023, working under Dr. Zachary Brunson and Dr. Aaron Stebner.

**Selected Projects**
- **Schlieren Imaging for Gas Flow Visualization in the Optomec DED Printer**  
Schlieren photography is a flow visualization technique that relies on light refraction to image changes in density of a fluid. This project aimed to characterize the unknown, system agnostic mass flow pattern and source that causes high variability and periodicity in mass flow amonog nominal DED printers. I was responsible for designing the system integration with the Optomec DED and project management to ensure in-situ and ex-situ testing of the system met timeline requiements.
[Poster PDF](/files/Schlieren_Poster.pdf) 

- **Alternative Sealing Methods for Density Testing of Porous Additively Manufactured Parts**  
This is an independent project I'm conducting that is funded by the Georgia Tech President's Undergraduate Research Award. Because additively manufactured parts are inherently porous, they require oil impregnation for 1+ hours in order to measure their density via Archimedes method. This proves inefficient for large batches. Therefore, I am testing the viability of alternate sealing methods, including vacuum sealing, heat shrink, and IPA impregnation.
[Whitepaper](/files/Density_Testing_Whitepaper.pdf)

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
