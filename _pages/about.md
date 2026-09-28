---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher in the Knowledge Representation Group at Leipzig University. My current research focuses on machine learning on graphs, particularly extensions of graph neural networks, their logical expressive power, their relationship to the Weisfeiler–Leman algorithm, and their computational properties.

I [completed](https://research.manchester.ac.uk/en/studentTheses/extended-counting-quantifiers-and-generalisations-of-the-fluted-f/) my PhD in Computer Science at the University of Manchester in 2025. My doctoral research concerned formal languages, particularly the decidability and complexity of finite and general satisfiability, query entailment, the existence of Craig interpolants, and spectra. I remain active in this area.

List of select publications ([also see DBLP](https://dblp.org/pid/346/5142))
======
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>