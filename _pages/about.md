---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Po-Chih from Taiwan. I graduated from the National Taiwan University, receiving both my master’s and bachelor’s degrees. I am passionate about robotics and have participated in many projects. For example, in my undergraduate research project, I developed 2 legged robots, in which I learned about basic control, computer vision, and ROS architecture. I was fascinated by the world of robotics and decided to dive deeper into this field. In my graduate research, I developed a unique surgical system to assist in infant cardiac surgery. This research was published at the IROS 2022, where I met many prestigious researchers and was amazed by their works. These experiences have convinced me to pursue an advanced degree, and I am looking for Ph.D. opportunities. If you are interested in my research or projects, you can check them in my portfolio, and please don’t hesitate to contact me!

News
======
[Dec 2022] I am hornerd to be awarded the 1st place in Youth Thesis Award by the [Chinese Institude of Electical Engineering](http://www.ciee.org.tw/)

[Oct 2022] I am presenting at the [IROS 2022](https://iros2022.org/), please check my publication [here](https://tobychen0106.github.io/publications/infant-Cardiac-Robotic-Surgical-System-(iCROSS))!

[Oct 2022] I started working as a Robotic Systems Engineer at [Mantis Robotics Inc.](https://www.mantis-robotics.com/)!

[Sep 2022] I just graduated from the [National Taiwan University](https://www.ntu.edu.tw/english/index.html)!

[Jan 2021] I am invited to a [talk](/talks/2021-01-28-GIS-Taiwan) at GIS Taiwan 2021 Summit!

Publications
======
{% for post in site.publications reversed%}
  {% include archive-single-cv.html %}
{% endfor %}


Projects
======
{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}