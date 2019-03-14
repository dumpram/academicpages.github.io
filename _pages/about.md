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

# Current student projects

{% include base_path %}

{% for post in site.topics reversed %}
  {% include archive-single.html %}
{% endfor %}
