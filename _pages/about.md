---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. Student from the School of Computer Science at the University of Manchester.
I am interested in expressivity of various formal languages and, in particular, the decidability and complexity status of
various problems (e.g. finite/general satisfiability, query entailment, Craig interpolant existence, spectra etc.) for said languages.

I am one of the inventors of the [Adjacent Fragment](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ICALP.2023.111) of
First-Order Logic and am currently working on expressiveness, spectra and decidability of satisfiability problems for extensions of the language.

I expect to finish my Ph.D. by end of March 2025, and am currently looking for post-doc opportunities. 

List of select publications <a href="{{ base_path }}{{ post.url }}/publications" rel="permalink">(see full list)</a>
======
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>