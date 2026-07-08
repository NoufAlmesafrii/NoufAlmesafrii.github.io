---
layout: single
title: "Nouf Almesafri"
permalink: /
author_profile: true
excerpt: "Senior Associate Researcher at TII working on computer vision, multimodal AI, vision-language models, and intelligent vision systems for prognostics, robotics, UAVs, and aerospace."
---

I am a Senior Associate Researcher at the Technology Innovation Institute (TII), Propulsion and Space Research Center (PSRC), Abu Dhabi, working in the Prognostics Team. My research focuses on Computer Vision, Multimodal AI, Vision-Language Models, and Intelligent Vision Systems, with applications in prognostics and health management, robotics, UAV perception, and aerospace systems.

## Research interests

- Computer Vision
- Vision-Language Models (VLMs)
- Vision-Language-Action models (VLA)
- Multimodal foundation models
- Image generation, reconstruction, and enhancement
- Video understanding, text-to-video, and video-to-text models
- Real-time visual perception
- Autonomous intelligent systems
- Physics-informed AI
- Digital twins and predictive maintenance

## Current focus

- Senior Associate Researcher, Prognostics Team, PSRC, TII
- Previous work in diagnosis and intelligent engine systems
- Industrial AI for PHM, predictive maintenance, and fleet health monitoring
- Research directions spanning robotics, UAVs, and aerospace systems

## Featured publications

{% for post in site.publications reversed limit: 3 %}
  {% include archive-single.html %}
{% endfor %}

[View all publications](/publications/)

## Featured projects

{% assign featured_projects = site.portfolio | sort: "date" | reverse %}
{% for post in featured_projects limit: 3 %}
  {% include archive-single.html %}
{% endfor %}

[View all projects](/projects/)

## Recent news

- 2026: Invited keynote speaker at the MFPT Conference.
- 2025: Published RAVEN in the PHM Society Asia-Pacific Conference.
- 2025: Released an arXiv preprint on event-based vision robustness for vehicle classification.

[More updates](/news/)