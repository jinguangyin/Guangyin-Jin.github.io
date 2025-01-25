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
5. IEEE Transactions on Cognitive Communications and Networking
6. IEEE Transactions on Artificial Intelligence
7. IEEE Transactions on Industrial Informatics
8. IEEE Transactions on Big Data
9. IEEE Internet of Things Journal
10. ACM Transactions on Knowledge Discovery from Data
11. ACM Transactions on Intelligent Systems and Technology
12. Information Sciences
13. Information Fusion
14. Data Mining and Knowledge Discovery
15. Applied Soft Computing
16. Neurocomputing
17. Artificial Intelligence Review
18. Pattern Recognition
19. Neural Networks
20. Transportation Research Part C: Emerging Technologies
21. IET Intelligent Transport Systems
22. Transportation Planning and Technology
23. International Journal of Digital Earth
24. Geo-Spatial Information Science
25. Cybernetics & Systems
26. Supercomputing
27. Cluster Computing
28. Applied Geography
29. Automation in Construction
30. Computers & Electrical Engineering
31. International Journal of Information Management Data Insights
32. Transportation Research Interdisciplinary Perspectives
33. Transportation Research

Program Committee Member for International Conferences
======
1. AAAI Conference on Artificial Intelligence (AAAI), 2023
2. AAAI Conference on Artificial Intelligence (AAAI), 2024
3. AAAI Conference on Artificial Intelligence (AAAI), 2025
4. Joint European Conference on Machine Learning and Knowledge Discovery in Databases (ECML-PKDD), 2023
5. Joint European Conference on Machine Learning and Knowledge Discovery in Databases (ECML-PKDD), 2025
6. International World Wide Web Conference (WWWW), 2023

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
