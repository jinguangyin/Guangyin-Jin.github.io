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
1. Workshop Chair, [IEEE the 1st International conference on Computer, Big Data and Artificial Intelligence (ICCBDAI 2020)](http://www.iccbdai.org/download/file/ICBDAI2020%20program2020-1018-1.pdf)
2. Workshop Chair, [IEEE the 3th International conference on Computer, Big Data and Artificial Intelligence (ICCBDAI 2022)](http://www.iccbdai.org/workshop2020/index.html)

Peer Reviewer for International Journals
======
1. IEEE Transactions on Knowledge and Data Engineering
2. IEEE Transactions on Neural Networks and Learning Systems
3. IEEE Transactions on Intelligent Transportation Systems
4. IEEE Transactions on Moblie Computing
5. Information Sciences
6. Information Fusion
7. Data Mining and Knowledge Discovery
8. Applied Soft Computing
9. 

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
