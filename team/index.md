---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Dagilis Lab is always looking for collaborators and trainees at various stages. If you are interested in joining the lab, email adagilis[at]uconn.edu with your CV as well as what projects in the lab you find most exciting.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: masters" %}
{% include list.html data="members" component="portrait" filters="role: undergraduate" %}
{% include list.html data="members" component="portrait" filters="role: mascot" %}

{% include section.html background="images/background.jpg" dark=true %}

Outside of the lab, we try to be somewhat social and enjoy the nature around Storrs. 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
