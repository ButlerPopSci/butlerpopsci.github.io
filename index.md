---
title: Home
---

{% include section.html
  dark=true
  size=wide%}
{:.center}
Butler Population Sciences is a team of researchers at the Gillings School of Global Public Health,  University of North Carolina, Chapel Hill.

{% include section.html
 background= "images/Textures_Tree2-1.png"
  dark=true
  size=wide%}

{% include section.html
  dark=false
  size=full%}

<!-- Block 1 -->
{% capture text %}
{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.png"
  link="research"
  title="Our Research"
  text=text
%}

<!-- Block 2 -->
{% capture text %}
{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

<!-- Block 3 -->
{% capture text %}

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/our_team.png"
  link="team"
  title="Our Team"
  text=text
%}
<!-- End section  -->

{% include section.html
 background= "images/Textures_Tree2-1.png"
  dark=true
  size=wide%}
