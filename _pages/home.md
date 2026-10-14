---
title: "Home"
layout: homelay
permalink: /
---

<h1 class="home-hero">{{ site.name }}</h1>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

<div class="chip-container" markdown="0">
<a href="{{ '/research' | relative_url }}" class="chip">Quantum Electrodynamics</a>
<a href="{{ '/research' | relative_url }}" class="chip">Path Integrals</a>
<a href="{{ '/research' | relative_url }}" class="chip">Superfluidity</a>
<a href="{{ '/research' | relative_url }}" class="chip">Parton Model</a>
<a href="{{ '/research' | relative_url }}" class="chip">Quantum Computing</a>
<a href="{{ '/research' | relative_url }}" class="chip">Nanotechnology</a>
</div>

Hello and welcome to my personal website, I’m happy to have you here!

The world can definitely be a disturbing place, but that’s not what I mean with this title. I actually quite love our planet and many aspects of the world we have created for ourselves. What I mean here is that I am an ecologist interested in how disturbances (like natural disasters, land-use alterations, and climate change) impact freshwater communities; and let me tell you, there are plenty of disturbances out there…
If you would like to learn more feel free to explore my page or reach out to me!

<div class="callout callout-success" markdown="0">
<div class="callout-title">{% include icon.html name="award" class="callout-icon" %} Nobel Prize in Physics, 1965</div>
<p>Awarded the Nobel Prize jointly with Julian Schwinger and Shin'ichiro Tomonaga for fundamental work in quantum electrodynamics, with deep-ploughing consequences for the physics of elementary particles.</p>
</div>

<div class="banner-frame" markdown="0">
<img src="{{ '/images/banner.webp' | relative_url }}" alt="Feynman diagrams" width="1400" height="449" loading="lazy">
<div class="banner-caption">Examples of Feynman diagrams. Feynman R., <em>The theory of positrons. Phys. Rev.</em> (1949)</div>
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

I am a physicist working in the field of quantum mechanics and quantum electrodynamics.
I received my undergraduate degree in physics from the Massachusetts Institute of Technology (MIT) in 1939 and went on to earn my PhD from Princeton University in 1942.
After completing my doctoral studies, I worked on the Manhattan Project, where I helped develop the first atomic bombs.
After the war, I returned to academia, holding teaching and research positions at Cornell and now at the California Institute of Technology.
