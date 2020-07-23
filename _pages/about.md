---
permalink: /
excerpt: "Salik Nadeem"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


About me
======

<span style="font-size:1.5em;">
I am a Computer Science graduate student under the supervision of Dr. Faisal Qureshi and a member of the [Visual Computing Lab](http://vclab.science.uoit.ca/) in the Faculty of Science at Ontario Tech University. Currently researching on cross-view human action recognition. I am deeply passionate about all-things deep learning; my area of focus is computer vision applications. Highly motivated to work in the industry and with academia, working on challenging AI problems. Other areas of interest include deep reinforcement learning, generative models and image processing.</span>
{: .notice}


Selected Projects
======

{% assign sorted_portfolio = site.portfolio | sort: 'priority' %}
{% for post in sorted_portfolio %}
  {% include archive-single.html %}
{% endfor %}



