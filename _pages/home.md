---
title: "Home"
layout: homelay
permalink: /
---

<h1 class="home-hero">{{ site.name }}</h1>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

<div class="chip-container" markdown="0">
<a href="{{ '/research' | relative_url }}" class="chip">Biomedical Health Informatics</a>
<a href="{{ '/research' | relative_url }}" class="chip">Bioinformatics</a>
<a href="{{ '/research' | relative_url }}" class="chip">Biomedical Image Processing</a>
<a href="{{ '/research' | relative_url }}" class="chip">Computer Vision</a>
<a href="{{ '/research' | relative_url }}" class="chip">Machine Learning</a>
<a href="{{ '/research' | relative_url }}" class="chip">Human&ndash;Computer Interaction</a>
</div>

I am a Master's student in Computer Science at the University of Calgary, working in the [Data and Network Sciences & Applications (DANSA) Lab](https://dansalab.cpsc.ucalgary.ca/profile.html?id=adnan-ferdous-ashrafi) under the supervision of Prof. Dr. Reda Alhajj.
My research is in biomedical health informatics: deep learning methods that learn from electronic health records and medical images, such as multi-modal networks for identifying rare diseases and graph-based networks for detecting autism spectrum disorder.

<div class="callout callout-success" markdown="0">
<div class="callout-title">{% include icon.html name="award" class="callout-icon" %} Graduate awards, University of Calgary</div>
<p>Recipient of the International Graduate Tuition Award (2025&ndash;2027) and the Alberta Graduate Excellence Scholarship (AGES), International (2026), both through the Faculty of Graduate Studies.</p>
</div>

{% capture selected %}{% bibliography --query @*[selected=true] %}{% endcapture %}
{% if selected contains "pub-entry" %}
## Selected publications

<div class="section-card selected-pubs" markdown="0">
{{ selected }}
<p style="margin: var(--space-4) 0 0;"><a href="{{ '/publications' | relative_url }}">All publications &rarr;</a></p>
</div>
{% endif %}

## About me

I received my B.Sc. (2014) and M.Sc. (2025) in Computer Science and Engineering from the Islamic University of Technology (IUT), Bangladesh, specializing in computer vision.
My B.Sc. dissertation proposed an algorithm for de novo DNA motif finding, and my M.Sc. dissertation developed graph-based neural networks for detecting autism spectrum disorder from multi-modal data.

From 2015 to 2025 I was a faculty member in the Department of CSE at Stamford University Bangladesh, rising from Lecturer to Senior Lecturer and also serving as an Assistant Proctor.
I also trained professionals in software architecture and design for the SEIP-BASIS project of the Finance Division, Ministry of Finance, Bangladesh.
At the University of Calgary I am a Graduate Assistant (Teaching) in the Department of Computer Science.

Outside research, I enjoy solving Rubik's cubes, collecting fountain pens, and watching classic films from before the 1980s.
