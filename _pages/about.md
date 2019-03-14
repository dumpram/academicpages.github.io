---
permalink: /
title: "Ivan Puri Pavić (@dumpram)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm PhD student on Faculty of Electrical Engineering and Computing, University of Zagreb. 
This site contains projects, publications and information about my research work.

# Research area

My main research area is _real-time scheduling in mixed-criticality systems_.
This includes embedded real-time systems and applications. However, I am 
interested in other research areas:

* digital signal processing,
* compressive sensing,
* machine learning.

# Current student projects

{% include base_path %}

{% for post in site.topics reversed %}
  {% include archive-single.html %}
{% endfor %}
