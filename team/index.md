---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We're a dynamic mix of computer visionaries, graphics wizards, and knowledge architects, all united by a passion for interactive media. We thrive on collaboration and innovation, bringing diverse perspectives to solve complex challenges. We're not just researchers; we're creators, explorers, and pioneers.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="active == true and role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="active == true and role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="active == true and role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="active == true and role != 'principal-investigator' and role != 'postdoc' and role != 'phd'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

# Former Members

{% include list.html data="members" component="portrait" filter="active == false" %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
