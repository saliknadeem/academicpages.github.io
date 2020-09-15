---
permalink: /
title: ""
excerpt: "Salik Nadeem"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
thumbnail: "/images/thumb.jpg"
---


About me
======

<span style="font-size:1.5em;">
I am a Computer Science graduate student under the supervision of Dr. Faisal Qureshi and a member of the [Visual Computing Lab](http://vclab.science.uoit.ca/){:target='_blank'} in the Faculty of Science at Ontario Tech University. My research is focused on cross-view human action recognition using unsupervised motion representation learning.
<br><br>
My research interests are:
Computer Vision, Deep Learning, Image Processing, Deep Reinforcement Learning, Generative Models, Scene Understanding.
<br><br>
I also love the art of storytelling and work as an animation artist in my free time. [Demo Reel](https://www.youtube.com/watch?v=pjJiOM3xar8)
</span>
{: .notice}


Select projects
======

{% assign sorted_portfolio = site.portfolio | sort: 'priority' %}
{% for post in sorted_portfolio %}
  {% include archive-single.html %}
{% endfor %}



