---
layout: archive
title: "Professional Activities"
permalink: /talks/
author_profile: true
---

List of Dr. Guangyin Jin's honorary appointments, participation in organizing conferences, serving as an academic editor and reviewer, and other academic activities.

Honorary Appointment
======
1. Visiting Professor, School of Continuing Education, Nanjing University of Science and Technology   
2. Senior Engineer, National Academy of Artificial Intelligence (NAAI)    

Editor
======
1. Academic Editor, [Plos One (SCI Index)](https://journals.plos.org/plosone/static/editorial-board?)   
2. Editorial Board Member, [Artificial Intelligence and Autonomous Systems](https://www.elspub.com/journals/artificial-intelligence-and-autonomous-systems/editorial/)   
3. Editorial Board Member, [Information System and Smart City](https://ojs.acad-pub.com/index.php/ISSC/about/editorialTeam)   
4. Editorial Board Member, [Computer Engineering (Chinese Journal)](https://www.ecice06.com/CN/news/news6495.shtml)    

Conference Organisation
======
1. 

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
