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
3. Special Expert, CNKI Nebula Expert Database
4. Distinguished Expert, Shenzhen Boku Talent Technology Group

Editor
======
1. Associate Editor, [Plos One (SCI Index)](https://journals.plos.org/plosone/static/editorial-board?)   
2. Associate Editor, [Artificial Intelligence and Autonomous Systems](https://www.elspub.com/journals/artificial-intelligence-and-autonomous-systems/editorial/)
3. Associate Editor, [AI+](https://www.elspublishing.com/journals/aiplus/editorial/)
4. Editorial Board Member, [Journal on Big Data](https://www.techscience.com/jbd/editors)
5. Editorial Board Member, [Information System and Smart City](https://ojs.acad-pub.com/index.php/ISSC/about/editorialTeam)   
6. Editorial Board Member, [Computer Engineering (Chinese Journal)](https://www.ecice06.com/CN/news/news6495.shtml)    

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
12. ACM Transactions on Spatial Algorithms and Systems
13. Information Sciences
14. Information Fusion
15. Data Mining and Knowledge Discovery
16. Knowledge and Information Systems
17. Applied Soft Computing
18. Neurocomputing
19. Artificial Intelligence Review
20. Pattern Recognition
21. Neural Networks
22. Transportation Research Part C: Emerging Technologies
23. IET Intelligent Transport Systems
24. Transportation Planning and Technology
25. International Journal of Digital Earth
26. Geo-Spatial Information Science
27. Cybernetics & Systems
28. Supercomputing
29. Cluster Computing
30. Applied Geography
31. Automation in Construction
32. Computers & Electrical Engineering
33. International Journal of Information Management Data Insights
34. Transportation Research Interdisciplinary Perspectives
35. Transportation Research

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
