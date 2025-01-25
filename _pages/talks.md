---
layout: archive
title: "Professional Activities"
permalink: /talks/
author_profile: true
---

Honorary Appointment
======
1. Visiting Professor, School of Continuing Education, Nanjing University of Science and Technology (teaching information engineering)
2. Senior Engineer, National Academy of Artificial Intelligence (NAAI)


{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
